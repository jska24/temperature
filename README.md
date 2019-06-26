public class Temperatura {
    public static void main(String[] args){
        int t1 = 7;
        int t2 = -5;

        checkTemp(t1);
        checkTemp(t2);
    }

    private static boolean checkTemp(int k){
        boolean isGreater = k>0;

        if(isGreater) System.out.println("Temperatura " + k + "*C jest wieksza od 0.");
        else System.out.println("Temperatura " + k + "*C jest mniejsza od 0.");

        return isGreater;
    }
}
