//Danny Speagle
//COP2551.001
//Display my favorites
//This code assignment came from my 2015 class

#include<iostream>
#include<string>
using namespace std;

/***************** Prototypes ***********************/
void display(Favorites fav);
void getFood(string& food);
string getMovie();

/*************** Header ********************/

class Favorites
{
private:
	string cfood;
	string cmovie;
public:
//	void display();
	string getFood();
	string getMovie();
	void setFood(string f);
	void setMovie(string mm);

};

/*************** Method (or Member) Functions ********************/

string Favorites::getFood()
{
	return cfood;
}

string Favorites::getMovie()
{
	return cmovie;
}

void Favorites::setFood(string f)
{
	cfood = f;
}

void Favorites::setMovie(string mm)
{
	cmovie = mm;
}

void display()
{
	cout << "My favorite food is: " << cfoo
}


/********************** Main Driver *************************/
int main()
{

	//variables
	string food;	//user input
	string movie;	//user input

	//instantiate one class object
	Favorites fav;

	getFood(food);			//function to get input
	movie = getMovie();		//value returning function to get input from the user

	//prompt
	
	//validate

	//move into class
	fav.setFood(food);
	fav.setMovie(movie);

	//display the values in class
	display(fav);

	return 0;
}

/***************** Function Definitions *************************/

void getFood(string& food)
{
	//prompt user
	cout << "Enter favorite food: ";
	cin >> food;

	//validate
	while (food != null)
	{
		BLAH BLAH BLAH
	}

	//validate USING DIFFERENT CODE
	while (food.length() == 0)
	{
		cout << "Enter favorite food" << endl;
		cin >> food;
	}
}

string getMovie()
{
	//declare local variable
	string m;

	cout << "Enter favorite movie: ";
	cin >> m;

	while (m.length() == 0)
	{
		cout << "Enter favorite movie: ";
		cin >> m;

	}

	return m;
}

void display(Favorites fav)
{
	cout << "Favorite food is: " << fav.getFood() << endl;
	cout << "Movie food is: " << fav.getMovie() << endl;

}# Rachel
Main
