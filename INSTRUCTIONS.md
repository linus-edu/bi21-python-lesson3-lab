# Instruktioner

## Skapa nytt repo fron template

Skapa ett nytt privat repository på GitHub utifrån det här templaterepositoryt genom att trycka på "Use this template"
https://github.com/linus-edu/bi21-python-lesson3-lab

Namnge repot _lesson3-lab_

Välj **Private** repository


## Ge åtkomst till repository

Lägg till _linus-edu_ som Collaborator

´Settings -> Collaborators -> Add People´


## Klona repo i VSCode

#### Skapa en Access token

- ´Settings -> Developer settings -> Personal access tokens -> Generate new token´
- Ge access token ett namn och giltighetstid
- Bocka i "repo" och "workflow"
- Tryck på "Generate token" längst ner
- Spara nyckeln någonstans


#### Klona (hämta en kopia) av det nya repositoryt i VSCode

## Gör en ändring från VSCode

- Gör en ändring i det utcheckade repositoryt: Lägg till ditt namn i filen README.md
- Gör en commit med ändringen
- Använd Sync för att pusha committen till GitHub


## Skapa och lös en konflikt

- Ändra på ett ordet "OKÄNT" till "GitHub" README.md direkt på GitHub, detta kommer skapa en commit som inte finns lokalt
- Ändra på samma rad lokalt, men ändra "OKÄNT" till "VSCode" istället
- Gör en commit med ändringen från VSCode
- Gör en Sync och lös konflikten som uppstår