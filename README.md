import java.util.Scanner;

public class MovieDriver {

	public static void main(String[] args) 
	{
		Scanner keyboard = new Scanner(System.in);
		
		Movie movie = new Movie();
		
		
		System.out.println("Enter a movie title: ");
		movie.setTitle(keyboard.nextLine());
		
		System.out.println("Enter the rating: ");
		movie.setRating(keyboard.nextLine());
		
		System.out.println("Enter the total amount of tickets sold: ");
		movie.setSoldTickets(keyboard.nextInt());
		
		System.out.print(movie.toString());
	}

}
