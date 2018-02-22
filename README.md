# ProgramEligibiltyCriteria using git

var i=0;
var ComProgram=['1.)BCA','2.)BBA','3.)BCOM','4.)IHM','5.)FASHION'];
var SciProgram=['1.)BTECH in CSE','2.)BTECH in EEE','3.)BTECH in MECH','4.)BCA','5.)BTECH in POLY'];
var User1=[
{
Name:'Tushar',
Board:'Icse',
Per12:60,
Stream:'commerce'
}
];
var User2=[
{
Name:'Amit',
Board:'Cbse',
Per12:90,
Stream:'science'
}
];
function Outcome()
	{
	
		console.log("PROGRAM ELIGIBILITY CRITERIA:\n");
			
		console.log("\nUser1 Details:\n");	
		for(i;i<User1.length;i++)
		{
			console.log(User1[i]);	
		}
		console.log("\n checking whether user1 is eligible or not\n");
		console.log("\n..................... Loading...............\n");
		
		
			if(User1.Stream = 'commerce')
			{	
				console.log("\n user1 is of commerce background\n");
				console.log("\n List of all  programs eligible for\n");
				console.log(ComProgram);
				
			}
			
			else
			{
				console.log("\n user1 is of science background\n");
				console.log("\n List of all programs eligible for\n");
				console.log(SciProgram);
			}
		
	
	console.log("\nUser2 Details:\n");	
		for(i=0;i<User2.length;i++)
		{
			console.log(User2[i]);	
		}
		console.log("\n checking whether user2 is eligible or not\n");
		console.log("\n..................... Loading...............\n");
		
		
			if(User2.Stream = 'science')
			{	
				console.log("\n user2 is of science background\n");
				console.log("\n List of all programs eligible for\n");
				console.log(SciProgram);
				
			}
			
			else
			{
				console.log("\n user2 is of commerce background\n");
				console.log("\n List of all programs eligible for\n");
				console.log(ComProgram);
			}
	
	}
	Outcome();
