### Hi there I'm Jonviter 👋


```tsx


import React from 'react';
import {ProfileView} from './Component/ProfileView'

const myDailyRoutine = () : string => {
  return "Coding, Sleep and Reading"  
}

const mySkils = () : string => {
  return "Javascript, Typescript, HTML, CSS"  
}


export const AboutMe  = () => {

    return (
        <>
        <ProfileView 
            name="Jonviter Simbolon"
            email="dolijonviter17@gmail.com"
            job="Mobile Devepoper"
            experience="3 years"
        />
        <MyDailyRoutineView
            title="My Daily Routine"
            content={myDailyRoutine()}
        />
        <MySkillsView
            title="Skills"
            content={mySkils()}
        />
        
        </>
    )

}

```
