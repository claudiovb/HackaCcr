# Challenge

This is a project demo created for [CCR Hackaton](http://www.grupoccr.com.br/hackathonccr/) with the following problem to tackle:

        Generate ideas to improve truck drivers routine, 
        
        finding solutions to improve their life quality, on the roads, 
        
        principally in relation to the professionals physical and mental health.

## The idea birth

After talking to some truck drivers across countries and seeing the familiarity in their problems but also solutions already tackled in more evolved nations, we could find what we believe would be the optimal solution for Brazil.
The data obtained is ilustrated in the pie chart below
![Truck drivers problems](https://github.com/claudiovb/HackaCcr/blob/master/assets/meta-chart%20(2).png)

In order to achieve better confort for the driver, the idea to be developed aims to use Waze API(to be added on the app) to get the optimal route and possible routes in the way. Then doing a trace beetwen our data and the one acquired in order to personalize this experience for the driver. To create this personalised experience we intend to use a ML model and calculate the optimal distance with secure stops for sleeping and still arriving in the delivery point on the schedule.

### Folders

####  RodoApp
  This folder has the template for beggining the App, which can be seen on this [demo](https://www.figma.com/proto/cyffm46LlDvLbxWaV36zRf/Untitled?node-id=1%3A7&scaling=scale-down), the technology chosed was React Native. 
  
####  RodoPath
W used google-OR tools to calculate optimal routes beetwen different points on a map, to have information about the possiblities for the truck driver arrive at its desired location, then we get the time matches and check with other parameters focused in improve the professional health.

####  MLRouteOptimizerExample

This is a already trained dataset, which got a better explanation on its README, the goal here is to get the data obtained and train the network to ensure the best possible experience for the truck driver.


### Prerequisites and Installation

##### React Native
If you want a better understanding on React native please follow this tutorial: [Quick Start React Native](https://s-pace.github.io/react-native/docs/getting-started.html)

##### Google OR-tools

If you want a better understanding on Google OR-tools please follow this tutorial: [Getting Started OR-tools](https://developers.google.com/optimization/introduction/python)

##### XGBoost


If you want a better understanding on the machine leaning model please follow this tutorial: [Getting Started XGBoost](https://xgboost.readthedocs.io/en/latest/get_started.html)
Also there is more info about the repo which possibilited the development of the idea, inside the ML folder README

## Deployment

The app still needs better development before a deployment

## Authors

* **Kaue Cano** 
* **Estevan Pedro Wisoczynski Reboledo**
* **Claudio Felipe Carvalho Vilas Boas**

**Team 548**
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to CCR and Shawee to creating the environment for the idea creation.
