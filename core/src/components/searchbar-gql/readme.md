# ion-searchbar-gql

Searchbars represent a text field that can be used to search through a collection. They can be displayed inside of a toolbar or the main content.

A Searchbar-gql should be used instead of an input to search lists. A clear button is displayed upon entering input in the searchbar-gql's text field. Clicking on the clear button will erase the text field and the input will remain focused. A cancel button can be enabled which will clear the input and lose the focus upon click.



<!-- Auto Generated Below -->


## Usage

### Angular

```html
<!-- Default Searchbar -->
<ion-searchbar-gql></ion-searchbar-gql>

<!-- Searchbar with danger color -->
<ion-searchbar-gql color="danger"></ion-searchbar-gql>

<!-- Searchbar with value -->
<ion-searchbar-gql value="Ionic"></ion-searchbar-gql>

<!-- Searchbar with telephone type -->
<ion-searchbar-gql type="tel"></ion-searchbar-gql>

<!-- Searchbar with a cancel button and custom cancel button text -->
<ion-searchbar-gql showCancelButton cancelButtonText="Custom Cancel"></ion-searchbar-gql>

<!-- Searchbar with a custom debounce -->
<ion-searchbar-gql debounce="500"></ion-searchbar-gql>

<!-- Animated Searchbar -->
<ion-searchbar-gql animated></ion-searchbar-gql>

<!-- Searchbar with a placeholder -->
<ion-searchbar-gql placeholder="Filter Schedules"></ion-searchbar-gql>

<!-- Searchbar in a Toolbar -->
<ion-toolbar>
  <ion-searchbar-gql></ion-searchbar-gql>
</ion-toolbar>
```


### Javascript

```html
<!-- Default Searchbar -->
<ion-searchbar-gql></ion-searchbar-gql>

<!-- Searchbar with danger color -->
<ion-searchbar-gql color="danger"></ion-searchbar-gql>

<!-- Searchbar with value -->
<ion-searchbar-gql value="Ionic"></ion-searchbar-gql>

<!-- Searchbar with telephone type -->
<ion-searchbar-gql type="tel"></ion-searchbar-gql>

<!-- Searchbar with a cancel button and custom cancel button text -->
<ion-searchbar-gql show-cancel-button cancel-button-text="Custom Cancel"></ion-searchbar-gql>

<!-- Searchbar with a custom debounce -->
<ion-searchbar-gql debounce="500"></ion-searchbar-gql>

<!-- Animated Searchbar -->
<ion-searchbar-gql animated></ion-searchbar-gql>

<!-- Searchbar with a placeholder -->
<ion-searchbar-gql placeholder="Filter Schedules"></ion-searchbar-gql>

<!-- Searchbar in a Toolbar -->
<ion-toolbar>
  <ion-searchbar-gql></ion-searchbar-gql>
</ion-toolbar>
```


### React

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


### Vue

```html
<template>
  <!-- Default Searchbar -->
  <ion-searchbar-gql></ion-searchbar-gql>

  <!-- Searchbar with danger color -->
  <ion-searchbar-gql color="danger"></ion-searchbar-gql>

  <!-- Searchbar with value -->
  <ion-searchbar-gql value="Ionic"></ion-searchbar-gql>

  <!-- Searchbar with telephone type -->
  <ion-searchbar-gql type="tel"></ion-searchbar-gql>

  <!-- Searchbar with a cancel button and custom cancel button text -->
  <ion-searchbar-gql showCancelButton cancelButtonText="Custom Cancel"></ion-searchbar-gql>

  <!-- Searchbar with a custom debounce -->
  <ion-searchbar-gql debounce="500"></ion-searchbar-gql>

  <!-- Animated Searchbar -->
  <ion-searchbar-gql animated></ion-searchbar-gql>

  <!-- Searchbar with a placeholder -->
  <ion-searchbar-gql placeholder="Filter Schedules"></ion-searchbar-gql>

  <!-- Searchbar in a Toolbar -->
  <ion-toolbar>
    <ion-searchbar-gql></ion-searchbar-gql>
  </ion-toolbar>
</template>
```



## Properties

| Property           | Attribute            | Description                                                                                                                                                                                                                                                            | Type                                                                        | Default           |
| ------------------ | -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | ----------------- |
| `animated`         | `animated`           | If `true`, enable searchbar animation.                                                                                                                                                                                                                                 | `boolean`                                                                   | `false`           |
| `autocomplete`     | `autocomplete`       | Set the input's autocomplete property.                                                                                                                                                                                                                                 | `"off" \| "on"`                                                             | `'off'`           |
| `autocorrect`      | `autocorrect`        | Set the input's autocorrect property.                                                                                                                                                                                                                                  | `"off" \| "on"`                                                             | `'off'`           |
| `cancelButtonIcon` | `cancel-button-icon` | Set the cancel button icon. Only applies to `md` mode.                                                                                                                                                                                                                 | `string`                                                                    | `'md-arrow-back'` |
| `cancelButtonText` | `cancel-button-text` | Set the the cancel button text. Only applies to `ios` mode.                                                                                                                                                                                                            | `string`                                                                    | `'Cancel'`        |
| `clearIcon`        | `clear-icon`         | Set the clear icon. Defaults to `"close-circle"` for `ios` and `"close"` for `md`.                                                                                                                                                                                     | `string \| undefined`                                                       | `undefined`       |
| `color`            | `color`              | The color to use from your application's color palette. Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`. For more information on colors, see [theming](/docs/theming/basics). | `string \| undefined`                                                       | `undefined`       |
| `debounce`         | `debounce`           | Set the amount of time, in milliseconds, to wait to trigger the `ionChange` event after each keystroke.                                                                                                                                                                | `number`                                                                    | `250`             |
| `mode`             | `mode`               | The mode determines which platform styles to use.                                                                                                                                                                                                                      | `"ios" \| "md"`                                                             | `undefined`       |
| `placeholder`      | `placeholder`        | Set the input's placeholder.                                                                                                                                                                                                                                           | `string`                                                                    | `'Search'`        |
| `searchIcon`       | `search-icon`        | The icon to use as the search icon.                                                                                                                                                                                                                                    | `string`                                                                    | `'search'`        |
| `showCancelButton` | `show-cancel-button` | If `true`, show the cancel button.                                                                                                                                                                                                                                     | `boolean`                                                                   | `false`           |
| `spellcheck`       | `spellcheck`         | If `true`, enable spellcheck on the input.                                                                                                                                                                                                                             | `boolean`                                                                   | `false`           |
| `type`             | `type`               | Set the type of the input.                                                                                                                                                                                                                                             | `"email" \| "number" \| "password" \| "search" \| "tel" \| "text" \| "url"` | `'search'`        |
| `value`            | `value`              | the value of the searchbar.                                                                                                                                                                                                                                            | `null \| string \| undefined`                                               | `''`              |


## Events

| Event       | Description                                     | Type                                         |
| ----------- | ----------------------------------------------- | -------------------------------------------- |
| `ionBlur`   | Emitted when the input loses focus.             | `CustomEvent<void>`                          |
| `ionCancel` | Emitted when the cancel button is clicked.      | `CustomEvent<void>`                          |
| `ionChange` | Emitted when the value has changed.             | `CustomEvent<SearchbarGqlChangeEventDetail>` |
| `ionClear`  | Emitted when the clear input button is clicked. | `CustomEvent<void>`                          |
| `ionFocus`  | Emitted when the input has focus.               | `CustomEvent<void>`                          |
| `ionInput`  | Emitted when a keyboard input ocurred.          | `CustomEvent<KeyboardEvent>`                 |


## Methods

### `getInputElement() => Promise<HTMLInputElement>`

Returns the native `<input>` element used under the hood.

#### Returns

Type: `Promise<HTMLInputElement>`



### `setFocus() => void`

Sets focus on the specified `ion-searchbar`. Use this method instead of the global
`input.focus()`.

#### Returns

Type: `void`




## CSS Custom Properties

| Name                        | Description                              |
| --------------------------- | ---------------------------------------- |
| `--background`              | Background of the searchbar              |
| `--cancel-button-color`     | Color of the searchbar cancel button     |
| `--clear-button-color`      | Color of the searchbar clear button      |
| `--color`                   | Color of the searchbar text              |
| `--icon-color`              | Color of the searchbar icon              |
| `--placeholder-color`       | Color of the searchbar placeholder       |
| `--placeholder-font-style`  | Font style of the searchbar placeholder  |
| `--placeholder-font-weight` | Font weight of the searchbar placeholder |
| `--placeholder-opacity`     | Opacity of the searchbar placeholder     |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
