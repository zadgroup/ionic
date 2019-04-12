```tsx
import React from 'react';

import { IonSearchbarGql, IonToolbar } from '@ionic/react';

const Example: React.SFC<{}> = () => (
  <>
    {/*-- Default Searchbar --*/}
    <IonSearchbarGql></IonSearchbarGql>

    {/*-- Searchbar with danger color --*/}
    <IonSearchbarGql color="danger"></IonSearchbarGql>

    {/*-- Searchbar with value --*/}
    <IonSearchbarGql value="Ionic"></IonSearchbarGql>

    {/*-- Searchbar with telephone type --*/}
    <IonSearchbarGql type="tel"></IonSearchbarGql>

    {/*-- Searchbar with a cancel button and custom cancel button text --*/}
    <IonSearchbarGql showCancelButton cancelButtonText="Custom Cancel"></IonSearchbarGql>

    {/*-- Searchbar with a custom debounce --*/}
    <IonSearchbarGql debounce={500}></IonSearchbarGql>

    {/*-- Animated Searchbar --*/}
    <IonSearchbarGql animated></IonSearchbarGql>

    {/*-- Searchbar with a placeholder --*/}
    <IonSearchbarGql placeholder="Filter Schedules"></IonSearchbarGql>

    {/*-- Searchbar in a Toolbar --*/}
    <IonToolbar>
      <IonSearchbarGql></IonSearchbarGql>
    </IonToolbar>
  </>
);

export default Example;
```
