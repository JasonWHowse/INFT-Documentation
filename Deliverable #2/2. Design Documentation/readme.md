2. Design Documentation
Numerous design techniques exist, several of which are described in Sommerville’s book. Which techniques you should use for a given project depends on the type of project, and what works best for you and your team. Some techniques are not suitable for some programs. For example, a detailed data flow diagram will probably be of little use if you are building a simple calculator application. The overriding goal is that the designs should be understandable. They should clearly indicate how the requirements will be implemented. Some of the more useful, and versatile, techniques are:
1. Architecture diagrams
These show the various components that will be used and how they fit together. For software built using an object-oriented language, a UML class diagram is essential. If a procedural language is used, a diagram showing the hierarchical relationship of the various modules and methods works well. You must have at least one architecture diagram in your design documentation — a diagram that shows how the various components of your software fit together.
2. Pseudocode
Pseudocode is extremely useful when designing individual methods. The use of pseudocode has all but replaced the common flow chart. If done well, it can be incorporated into comments used for source code.
3. Decision Tables
Decision tables are valuable when a course of action depends on a particular combination of values. A decision table shows all possible combinations of a set of values, and indicates what should happen for each combination.
4. Control Diagrams
These include such diagrams as state-transition diagrams and activity diagrams.
You should indicate how your requirements trace to your designs, by identifying each design component using the identifier(s) of the requirement(s) that component is designed to meet. The following hypothetical pseudocode shows an example:
// Pseudocode for allowing user to choose variant of poker to play
// (Requirement 2.0.0)
//
// Assumes user has chosen the “New Game” menu option
display GUI dialog showing available game variants (5-card draw, 7-card stud, Texas Hold’em)
if (choice == 5-card draw)
initialize 5-card draw game
else if (choice == 7-card stud)
initialize 7-card stud game
else if (choice == Texas Hold’em)
initialize Texas Hold’em game
One or two simple diagrams won’t cut it for your design documentation. Your project should be complex enough to require more than that. But there is no “target” number of diagrams necessary to get all the points for this part. I can’t set a target because I don’t know in advance what your project will be, and even if I did, I have no way of knowing what approach you will take to build the project. Keep in mind, the goal is for you to understand the problem you are solving before you start writing copious amounts of code. You need to convince me that you didn’t just sit down at your source code editor and hack out the program with all the designs in your head, or made up as you went along.