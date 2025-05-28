public class Main {
    public static void main(String[] args) {
        int [] a={5,1,6,3,2,4};
        int n=a.length;
        for(int i=0;i<=n-2;i++){
            for(int j=i+1;j<=n-1;j++){
                System.out.println(a[i]+","+a[j]);
            }
        }
    }
}
