# Push_zeroes_to_end
//push zeroes to end in a given array.....
void pushzerotoend(int n,int input[100]){
    int k=0;
    for(int i=0;i<n;i++){
        if(input[i]!=0){
            int temp=input[i];
            input[i]=input[k];
            input[k]=temp;
        }
    }
}
