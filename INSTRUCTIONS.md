# Instruktioner

## Skapa nytt repo från template

Skapa ett nytt privat repository på GitHub utifrån det här templaterepositoryt genom att trycka på "Use this template"

https://github.com/linus-edu/bi21-python-lesson3-lab

Namnge repot _lesson3-lab_

Välj **Private** repository


## Ge åtkomst till repository

Lägg till _linus-edu_ som Collaborator

`Profilbild -> Settings -> Collaborators -> Add People`


## Klona repo i VSCode

#### Skapa en Access token

- `Profilbild -> Settings -> Developer settings -> Personal access tokens -> Generate new token`
- Ge access-token ett namn och giltighetstid
- Bocka i "repo" och "workflow"
- Tryck på "Generate token" längst ner
- Spara nyckeln någonstans


#### Klona det nya repositoryt från VSCode

Från tabben Source Control

## Gör en ändring från VSCode

- Gör en ändring i det utcheckade repositoryt: Lägg till ditt namn i filen README.md
- Gör en commit med ändringen
- Använd Sync för att pusha committen till GitHub


## Skapa och lös en konflikt

- Ändra filen README.md direkt på GitHub: Byt ut ordet "OKÄNT" till "GitHub", detta kommer skapa en ny commit som inte finns lokalt
- **Utan** att köra Sync först: Ändra på samma rad lokalt, men byt "OKÄNT" till "VSCode" istället
- Gör en commit med ändringen i VSCode
- Gör en Sync och lös konflikten som då uppstår
