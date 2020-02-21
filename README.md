# 🤖 Random Robots [Work in Progress]

THREE.js evolution experiment with randomly generated "robots".

This application will generate a robot where the size, number of parts, types of parts, and specifications of parts are all random. That robot will then have 30 seconds to score as highly as possible, where "score" is a measure of distance travelled.

Once 100 robots have been generated, their scores will be compared. The 50 lowest scoring robots will be discarded and the top scoring 50 robots will be randomly mutated. After this, the whole experiment will be run again for the next generation of robots.

In theory, each successive generation of random robots should on average score better than the previous generation. This experiment is largely inspired by this [YouTube Evolution Simulator series](https://www.youtube.com/watch?v=GOFws_hhZs8) and by the [Ikea + Teenage Engineering collaboration](https://design-milk.com/teenage-engineerings-3d-printables-transform-ikea-speakers-into-something-cool/) for the look and feel.

## 🏃‍♂️ Up and Running

1. `git clone https://github.com/themarkappleby/random-robots.git`
1. `cd random-robots`
1. `yarn install`
1. `yarn start`
1. Open http://localhost:8080/ in your browser

## 🌎 Global Dependancies

- [Node.js](https://nodejs.org/en/)
- [Yarn Package Manager](https://yarnpkg.com/getting-started/install#global-install)
