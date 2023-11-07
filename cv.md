# **Aliaksandr Yurhilevich**

## My Contact Info:

- Phone: +375 25 92-888-55
- E-mail: MrUnderSan@gmail.com
- LinkedIn: [MrUnderSan](https://www.linkedin.com/in/mrundersan/ "LinkedIn")
- GitHub: [MrUnderSan](https://github.com/MrUnderSan "GitHub")
- Telegram: [MrUnderSan](https://t.me/MrUnderSan "Telegram")
- Instagram: [MrUnderSan](https://www.instagram.com/mrundersan/ "Instagram")

## About Me

I am 30 years old, and I have always been interested in IT and software engineering. That's why I decided to start learning web development. Now, I believe my skills and abilities are enough to get job in front-end development.

## Skills

- React
- Redux
- TypeScript
- JavaScript
- Git/GitHub
- CSS (SCSS)
- HTML

## Code Examples

```
export const todolistsReducer = (state = initState, action: ActionsType): TodolistType[] => {
    switch (action.type) {
        case 'ADD-TODOLIST':
            const newTodolist: TodolistType = {id: action.payload.id, title: action.payload.title, filter: 'all'}
            return [...state, newTodolist]
        case 'REMOVE-TODOLIST':
            return state.filter(t => t.id !== action.payload.id)
        case 'CHANGE-TODOLIST-TITLE':
            return state.map(t => t.id === action.payload.id ? {...t, title: action.payload.title} : t)
        default:
            return state
    }
}

```

## Experience

2009-2012.  
Founder and administrator of **UnderMusic.Org**, popular Belarusian music portal on the Guest ByFly Internet. Created on the CMS DataLife Engine.

## Education

Belarusian State Agrarian Technical University  
Engineer's degree, Energy Supply (Electric Power Industry)  
2011-2016

## Courses

- Udemy: WEB-developer 2021 by Ivan Petrychenko: _100% received the Certificate_
- Udemy: The Complete JavaScript + React Course - from scratch to result by Ivan Petrychenko: _50% completed_
- RS School: JS/FE Pre-School 2022: _100% received the Certificate_
- RS School: JavaScript/Front-end 2022Q1: _Completed stage 1_
- IT-INCUBATOR: Front-End Development: _Studying since July 2023 until now_

## Languages

- Belarusian - native speaker
- Russian - native speaker
- English - A2+...
