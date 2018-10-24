# Orion 2.0 Requirements
### October 2018

Orion is een systeem voor het bijhouden van de verrichtingen van studenten.


## Functional requirements

    Orion will never, repeat NEVER, draw its own conclusions and provide end results without human intervention.


### Most prominent changes w.r.t. Orion 1

- API
- mobile app
- notifications
- more user responsibility: zelf inschrijven bij lessen, docent kan lessen en groepen aanmaken, studenten toevoegen etc.
- more flexibility w.r.t. module configuration (e.g. special basics) en bv. lesreeksen die onder meerdere modules hangen
- gedifferentieerde beoordelingen (bolletjes/formulieren) geintegreerd (ook herkansingsmogelijkheid) en flexibel aan te maken
- conform GDPR
- dashboard
- gedeelde verantwoordelijkheid beoordelingen (soort van 'lessen delen' maar dan op natuurlijke manier)
- eenvoudiger onderhoud voor tutoren (o.a. afschaffen van trajecten)
- search engine
- on-topic help instructions
- rule sets (e.g. minimaal zoveel workshops volgen)

### Generic requirements

User friendliness
- easy login
- default entry page
- user preferences


User types & permissions
- admin
- teacher
- tutor
- student

* default use
* custom use


## Which kinds of data will be managed?

- school/education

- student: pre-course, Bachelor and Master
  - general info & picture
  - participation in classes: predetermined and by signing up
  - assignments given
  - feedback on various levels

- teacher
  - general info & picture

- tutor
  - general info & picture

- absence of student and teacher (ziekmelding)

- lesmateriaal? Links naar andere systemen? Let op: dit gaat over
  jaargrenzen heen. Punt van discussie.

- slides e.d. die bij een les behandeld zijn

### Screens & views

- overzicht ingeleverde opdrachten met download-mogelijkheid
- mutatie-overzichten, met name 'wat moet ik nog doen'
- user page: profile, upload new picture, enter courses
- docenten kunnen zelf lessen aanmaken & studenten toevoegen/verwijderen, eventueel met bevestiging door of signaal naar tutor
- docent kan zelf groepen maken
- student centered/teacher centered/class centered...
- link lesweken aan kalender
- voor studenten: overzichtspagina met deadlines

### Connection to other systems

- Osiris: inzage 
- Octo en dergelijke: inzage


## Statistics


## Notifications

For students:
- teacher absent
- assignment deadline

For teachers:
- new uploads
- assignment deadlines
- oranje modules


### Fun
- random beurt generator
- sound effects :-)


## Technical requirements
## Frameworks
Frameworks nemen een hoop werk uit handen, bevatten i.h.a. goed geteste
constructies waarmee je een boel tijd bespaart en dwingen consistent
gebruik af, wat ten goede komt aan de uniformiteit en intuitiviteit van de
user interface.

Nadeel is dat custom wensen waarin niet voorzien is beter vermeden kunnen
worden omdat die het framework breken of ingewikkeld te implementeren zijn.

Eisen aan frameworks:

- goed onderhoudbaar
  - binnen onze gelederen moeten voldoende mensen zijn die dit kunnen en
    met de benodigde talen en subsystemen overweg kunnen
  - niet nodeloos ingewikkelde hosting-eisen
  - uitbreidingen
- goed forkbaar
- veelzijdig
  - moet minimaal de nu vereiste tools en modules bevatten
  - moet uitwisselmogelijkheden met andere systemen hebben
  - extensies voor bv. mobiele toepassing
  - snel
- goede security
- toekomstvast
- stabiel (redelijk uitontwikkeld)
- open source
- community
- documentatie


## User support
Met name herstellen van gebruikersfouten moet minder tijdrovend, dus
bv. meer via GUI

User support moet beschikbaar zijn op kritieke examenmomenten.

## Maintenance
Each school provides maintaining staff.


## API
Orion 2 must have an API for others to extend & build their own apps

