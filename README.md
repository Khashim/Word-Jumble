/**************************************************************************
*     Kewther Hashim
*     Mrs.Kirby
*     Dev C++ 5.11
*     January 9th 2019
*     Purpose: Game Pack Summative (Word Jumble)
**************************************************************************/


#include<iostream>
#include<string>
#include<cstdlib>
#include<ctime>

using namespace std;
char c = 'Y';

int main()
{
	int score;
	score=0;
	string TheWords;
	string ;
	
string words[WORDS] =
{
	
{"antidisestablishmentarianism"},
{"floccinaucinihilipilification "},
{"pneumonoultramicroscopicsilicovolcanoconiosis"},
{"spectrophotofluorometrically "},
{"hepaticocholangiogastrostomy "},
{"psychoneuroendocrinological"},
{"radioimmunoelectrophoresis "},
{"pneumoencephalographically"},
{"thyroparathyroidectomized "},
{"psychophysicotherapeutics ",}
};

srand(time(0));
int choice=(rand() % WORDS)
string words=WORDS;\

string jumble=TheWords;
int length=jumble.size();


cout<<"\nWelcome to Word Jumble.\nDo you know how to play?->(Y/N)";
	cin>>c;
	
	if (c!='Y')
	{
		cout<<"Thats okay! Here are the rules:\n\nThere have been a selection of words chosen that when is presented to you, will seem jumbled.\nTo win, you have to guess what he word was orginally before your three tries are over.\n\nThink you can do it?->(Y)";
		cin>>c;
		cout<<"Great! Let's start our game!";
	}	
	else
	{
		cout<<"Great! Let's start our game!";
	}
	
	cout<<"Your word is"<<jumble;
	string guess;
	cout<<"What is the original word?->";
	cin>>guess:
	
	if ((guess=The Word))
	{
         cout<<"YOU GOT IT!! GREAT JOB!";
    }
	else
	{
	cout<<"Sorry...Better luck next time.";	
	}
	
}
