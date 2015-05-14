public class Pyramid{
  public static void main(String[] args){
      int i;
      int j;
      int k;
      String spasi = " ";
      String p = "X";
        for (i=1; i<=8; i++){
          for (j=i; j<=8; j++){
          System.out.print(spasi);
          }
          for (k=1; k<=(2*i); k++){
          System.out.print(p);
          }
      System.out.println();
      }
    }
  }
