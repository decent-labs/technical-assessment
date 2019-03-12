# Technicals Test

The purpose of this repository is to describe a system which should be implemented, in order for decent to gain a greater understanding of the technical capabilities of the applicant.

## Best Practices

We'd like to see proficiency with the following technologies, methodologies, and systems:

* Git
  * Branching strategies
  * Atomic commits
* Docker
  * Local development environment
    * `docker-compose`
  * Don't reinvent the wheel - use existing tools where appropriate
* Database
  * Creation scripts
  * Migrations scripts
  * Local development
    * Using `Dockerfile` for a popular database solution, paired with `docker-compose`
* Backend
  * API structure
  * Informative `README` to get a new developer up and running
  * Test suite
* Frontend
  * Fully client-side Javascript app, strongly recommend using a framework like React (or Gastby)
  * Informative `README` to get a new developer up and running
  * Test suite
  * Usage of layout system (e.g. Bootstrap, Material, Foundation)


Ideally, you are familiar with the concepts of a [12 Factor App](https://12factor.net/), and can implement the project using those methodologies.

## Project Details

Please build a "To Do" app. This To Do app should consist of:

* Persistence layer
  * Some sort of database to enable state over time
  * Use Postgres, MySQL, or some other production-quality DB of your choice. Hint: using Docker is totally sufficient here
* Backend API
  * User accounts, to support multiple users
  * CRUD To Do functionality
  * Build with NodeJS, Golang, or other server-side language of your choice
* Frontend
  * Client side React frontend which interacts with API
  * A "clean" design
    * Looking for functionality over form, but if you can slap a good design on this, that's great :)
    * At the very least, use an existing layout system (Bootstrap, Material, Foundation, etc) to make it not-totally-ugly.
* General Features which entire system should support:
  * New User creation
  * Create To Do
  * Edit To Do
  * Delete To Do
  * "Complete" To Do
  * List all outstanding To Dos
  * List completed To Dos
  * Nice to have:
    * Different "categories", or "lists", each consisting of their own set of To Dos

It's not necessary that any of this is hosted anywhere. However, there should be easy-to-follow instructions to allow a developer (like us at Decent) to get up and running with this solution on their own development machines.

It's completely appropriate that this solution consists of multiple git repositories, which contain the different projects (backend & frontend).

Please direct and questions or concerns to Adam <adam@decentcrypto.com>

Thanks!
