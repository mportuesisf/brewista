# brewista
Coffee brew ratio app for Casio and TI-84 calculators. 

This app is written in BASIC language for TI-84 series calculators (84+, CE, and likely the Evo) and the Casio fx-9860Giii, fx-9750Giii, fx-CG50 and similar calculators. It calculates the optimal dosage of water and coffee for various brewing methods.  Also calculates the amount of the finished brew, as well as caffeine per serving.

## Installation

See the manufuacturer's documentation for help with installing BASIC programs on your particular calculator.

### TI 84
Download the `.8xp` file and install from a PC or Mac using TI Connect CE software.

### Casio
Install the `.txt` file from a PC or Mac into the appropriate folder.  See Casio's documentation for more details.

## Usage

### Getting Started

Launch the program on your calculator. On the TI, press the `PRGM` key and select from the menu. On the Casio, press Menu, then `PRGM`, then select from the menu.

### Data Entry

The program opens with the following screen:

TODO pic

Choose *Water Needed* to calculate the water necessary for a given amount of ground coffee, or *Coffee Needed* to determine the proper amount of ground coffee for a given amount of water.

The next screen displays a set of brewing methods.  Choose one to determine the proper brew ratio for that style of brewing.

TODO pic

* *Auto-drip*: automatic drip coffee makers (ratio: 18 parts water:1 part coffee by weight)
* *Pour-over*: single serving pourovers, using a pourover dripper such as a Chemex, Hario V60 or Melitta (ratio: 16.6:1)
* *French Press*: coffee steeped in a French press pot (ratio: 15:1)
* *Cold Brew*: Cold brew coffee concentrate, brewed at room temperature or in the refrigerator for 12-24 hours (ratio: 5:1)
* *Moka 3-cup*: coffee brewed in a 3-cup Moka Pot (ratio: approximately 8:1)
* *Moka 6-cup*: coffee brewed in a 6-cup Moka Pot (ratio: approximately 8.5:1)
* *Custom ratio*: Enter a custom brew ratio (in parts water, i.e. X parts water to 1 part coffee)

The next screen asks for a serving size (in ml). 

TODO pic

Enter `0` to accept its default suggestion (usually 250 ml, but varies depending upon the chosen brewing method), or enter your own serving size.

### Results

The calculator displays the following results for your chosen brew:

* *Coffee*: dose in grams
* *Water*: dose in milliliters
* *Brews*: Volume of brewed coffee, taking into account absorption of water by the coffee grounds
* *Srvs*: Number of servings given the volume of brewed coffee, and the chosen serving size
* *Serv Sz*: Serving size in milliliters, as previously entered
* *Arabica*: Caffeine per serving (in mg), assuming 100% Arabica beans
* *Robusta*: Caffeine per serving (in mg), assuming 100% Robusta beans

Press the `ENTER` (TI) or `EXE` key (Casio) to return to the main menu.
