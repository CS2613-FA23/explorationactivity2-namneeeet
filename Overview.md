## Package/ Library Overview

Team Members: Namneet Singh Bamrah, Jack Hyun

#### Which package/library did you select?

The package I've selected for this exploration activity is pygame in python, along with pandas 

1.  What is the package/library?
 
        What purpose does it serve?
 
            The pandas library in python is used for analyzing, cleaning, exploring and manipulating data. So it is mainly working with data sets. This library is important for working in fields related to Data Science.
 
            The pygame is used for creating games by using images, sounds, etc. The program will display multiple images per second on the screen, based on the tick rate.
 
2.  How do you use it?
 
        You can just simply import the pandas/pygame from the library after install it.
 
    To install it?
 
        If you are using Visual Studio Code, open your terminal then simply type in "pip install pandas" . This will install every package you need to use pandas in python
 
        If you are using Mac, you have to ensure that you have python3 and pip3 up to date. You can check that by using:
        > python3 --version
        > pip3 --version
 
        If you want to make sure that your pip3 version run perfectlym you can update it by:
        > pip3 install --upgrade pip
   
        To install pandas, type : > "pip3 install pandas" in the terminal.
        To install pygame, type : > "pip3 install pygame"
   
    Function used when using pandas
 
    Dataframe()
 
            This function convert a array of data into a Dataframe ( use for multitple data input)
 
            Ex: data = pandas.DataFrame(sth)
 
    Basic function for pygame
 
    pygame.init()
 
            The init function is used to initialize all the pygame modules required for creating the game
 
    screen = pygame.display.set_mode(width, height)
 
            This line will create a black screen with the dimension specified by the user.
   
    clock = pygame.time.Clock()
    clock.tick(60)
 
            Here you create a clock class, then set the tick to 60
            It basically makes the game refresh 'x' number of times per second, depending on what value is used.
            In this case, 60 is chosen as the tick, which means that the game is refreshed 60 times every second.
 
    pygame.display.update()
 
            The main code will need to be updated per clock tick
            This function updates the display when called.
 
    pygame.display.set_caption("Tetris")
 
            This will set game's window title as "Tetris".
 
 
    Creating surface/area and display a images
 
            If something needs to be displayed to the screen, the surface function is used.
            The surface function creates a surface of specific dimensions to work with.

            Ex:
            color_surf = pygame.Surface((100,200))
            color_surf.fill('Red')
 
            # In this case, a surface of dimensions 100x200 is created, and then filled with the color red.
 
       
    Example block of code
 
            while True:
                #checks if "quit" is in the list of events and exits if true
                for event in pygame.event.get():
                    if event.type == pygame.QUIT:
                        pygame.quit()
                        sys.exit()
                    if event.type == pygame.KEYDOWN:
                        print('Down')
 
            In this example, since the game will run as long as the user does not exit the game, a while loop is used where the condition is always true.
 
            When the program is running, pygame has lots of events happen per frame.
            pygame.event.get() returns a list of events.
            event.type returns the type of an event. This can be used to track various inputs, including keypress, quitting the game, etc.
 
            You can explore more about the event type in pygame doc
 
    Display image on top of each other
 
            You can achhive this using blit (stands for block image transfer , which is basically a surface on another surface)
 
            ex:
                Let take the screen and the color_surf above
 
                screen.blit(color_surf, (x,y))
 
                Here x and y are the positions to place them.

                The blit function can also be used to add text to the screen (which is how the scores are displayed in the game).
 
 
       
       
4.  What are the functionalities of the package?/library?
 
    Pandas
    a  To analyze the data set from JSON, csv or excel file.
    b  To make a graph, calculate probability.
    c  Mainly for working with data sets
 
    Pygame
    a To create games in python, with easy and simple to read formatting.
 
6.  When was it created?
 
    Pandas was created in January 11 2008
    Pygame was created in October 28 2000
 
7.  Why did you select this package/library?
 
    I chose this library due to how accessible it is. It also has really simple and easy to read formatting, which is definitely a big plus point for beginners      trying to get into the field of game development. This library has also provided me the motivation to work more in the field of game development.
 
8.  How did learning the package/library influence your learning of the language?
 
    Learning pygame consisted of dealing with a lot of object oriented programming. This caused me to become fluent with OOP in python.
    Learning pandas caused me to research more about lists and dictionaries in python, which inturn made me more fluent in dealing with data structures.
 
 
10.  How was your overall experiences with the package/library?
 
    These libraries have been really fun and interesting to work on. Working on pygame and pandas have made me more fluent in python in general. Combining 2 
    completely different libraries together was a difficult task, but proved to be really beneficial.
    I would recommend these libraries to people who have learnt the basics of python. It would be quite difficult to use these libraries to their full potential     without knowing the basics of python.
    I would definitely continue using these libraries (pygame and pandas) as they're really beneficial for various different kinds of tasks (data handling, 
    using data in games, which are inturn created with pygame, etc)
 
## References
https://en.wikipedia.org/wiki/Pygame
https://www.pygame.org/docs/
 
