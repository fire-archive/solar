# Structure of game source code directories

Lee, K. Ernest. Online discussion. “Project directory structure.” 28 Apr. 2012 #wizardslair on irc.afternet.org. 28 Apr. 2012. Original source: Blackbird

Think of P as at the main project dir:

    P/Docs/ (if wanted)
    P/Dev/ (where dev happens)
    P/Dev/Source/ (your game source)
    P/Dev/Tools/ (put libraries here)
    P/Dev/Project (makefiles/ project files etc)
    P/Run/ (where testing happens)
    P/Run/Data (Game assets data that will be shipped with the game)
    P/Run/User (Game created files / configurations etc 'user data')

That is pretty much the jist of it.
