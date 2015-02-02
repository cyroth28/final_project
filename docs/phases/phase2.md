# Phase 2: JSON API and First Backbone Views

## Rails
### Models

### Controllers
Koach::PatientsController (update, index, show)
Koach::ExercisesController (create, update, destroy, index, show)

### Views
* blogs/show.json.jbuilder

## Backbone
### Models
* Exercise (parses nested `exercises` association)
* Patient

### Collections
* Patients
* Exercises

### Views
* Patients index
* Patient show
* Exercise new
* Exercise show
* Exercise edit