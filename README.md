# PP-4.1

public class NewMain {

    int goalsScored;

   public NewMain(){
       goalsScored = 0;
   }

    public void setGoal() {
        goalsScored++;
    }

    public int getGoal() {
       return goalsScored;
    }

}


public class NewMain1 {

   public static void main(String[] args) {

        NewMain team1 = new NewMain();
        NewMain team2 = new NewMain();

        System.out.println(team1.getGoal());

        team2.setGoal();

        System.out.println(team2.getGoal());

        team1.setGoal();
        team1.setGoal();

        System.out.println(team1.getGoal());

    }
}
