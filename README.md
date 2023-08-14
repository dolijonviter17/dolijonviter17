### Hi there I'm Jonviter 👋


```tsx


import React from 'react';
import {ProfileView} from './Component/ProfileView'

export interface ProfileParams {
  name: string;
  email: string;
  job: string;
}


const About : React.FC<ProfileParams> = ({name, email, job}) => {

    return (
        <ProfileView 
            name="Jonviter Simbolon"
            email="dolijonviter17@gmail.com"
            job="Mobile Devepoper"

        />
    )

}

```
