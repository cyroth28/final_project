# Koach App

[Heroku link][heroku]

[heroku]: http://flux-capacitr.herokuapp.com

## Minimum Viable Product
Koach is a program for physical therapists to have live video calls with patients.

- [x] Doctor log in and log out.
- [x] Doctors create and diagnose patients
- [x] Patient log in and log out
- [x] Doctors give and edit exercises for each patient
- [x] Integrate with a video chat API for synchronous telehealth communication with https://tokbox.com/

Wireframes
DB Schema
Implementation Timeline
Heroku Link

## Design Docs
* [View Wireframes][views]
* [DB schema][schema]

[views]: ./docs/views.md
[schema]: ./docs/schema.md

## Implementation Timeline

### Phase 1: User Authentication, with two types of users (~1 day)
I'll create the standard user authentication that we've learned, but create the
system for multiple types of users: both patients and doctors.  Doctors have the
ability to create users.

[Details][phase-one]

### Phase 2: JSON API and First Backbone Views (~2 days)
I'll create the backbone views and also the API for the exercises. The exercises
will be standard (coming from information that I've already got). Doctors will
drag and drop them from a library into the patient's program. They consist of a
name, description, set and rep scheme, and video URL.

[Details][phase-two]

### Phase 3: Integrate with third party API (~3 days)
I plan to use third-party API called Tokbox (www.tokbox.com) to add synchronous
video chat between doctors and patients. Tokbox has good documentation and
apparently plays well with backbone. I have no idea how that will work yet so I
estimate 3 days.

[Details][phase-three]

### Phase 4: UI (~3 days)
It will be made beautiful with JQuery, and I'll make each exercise program be
editable by double click for the doctor.

[Details][phase-four]

[phase-one]: ./docs/phases/phase1.md
[phase-two]: ./docs/phases/phase2.md
[phase-three]: ./docs/phases/phase3.md
[phase-four]: ./docs/phases/phase4.md
