# React exercise - Full Stack JavaScript Techdegree

### Planets application
This project is built using React to to display a list of planet cards.

***

## View project
:mag: Live version available at [nickhericks.github.io/reactPlanets/](https://nickhericks.github.io/reactPlanets/)

<img src="https://res.cloudinary.com/dtqevfsxh/image/upload/v1565022764/portfolio/planets.png" width="899px">

<!-- ## Project objective
This project was built as I was learning about the Express web framework and the Pug templating engine. Through this project I learned about the request and response objects, body-parser, routes, templates, middleware, cookies (cookie-parser) redirects, error handling, modularizing routes, route parameters and query strings, serving static assets with a static server, and much more. :) -->

<!-- ## Techniques and concepts
- Express web framework
- Pug templating engine -->

## Code example
```javascript
  // Render App component
  render() {
    return(
      <div className="container"> 
        { this.state.planets.map( planet => (
          <Planet
            key = {planet.id.toString()}
            name = {planet.name}
            diameter = {planet.diameter}
            moons = {planet.moons}
            desc = {planet.desc}
            url = {planet.url}
          />
        ))}
      </div>
    )
  }
```

## Acknowledgements
This project was built as part of the [Full Stack JavaScript Techdegree](https://join.teamtreehouse.com/techdegree/) offered by [Treehouse](https://teamtreehouse.com) :raised_hands:
