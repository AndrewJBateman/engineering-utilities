# :zap: Engineering Utilities NPM Module

* Converts engineering data and supplies useful information to the Engineer.

**Note:** to open web links in a new window use: _ctrl+click on link_

## :page_facing_up: Table of contents

* [:zap: Engineering Utilities NPM Module](#zap-engineering-utilities-npm-module)
  * [:page_facing_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal_strength: Technologies](#signal_strength-technologies)
  * [:floppy_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status & To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* engineering-utilities supports 2 options:

* *shadow_type* - _hard / soft_ (defaults to soft)
* *padding* - _boolean_ (Defaults to false)

## :camera: Screenshots

![Example screenshot](./img/.png).

## :signal_strength: Technologies

* [npm](https://www.npmjs.com/)

## :floppy_disk: Setup

* To install this module type `npm i engineering-utilities --save` then add to your project:

```javascript
import { engineeringUtilities } from 'engineering-utilities'

engineeringUtilities({
  shadow_type: 'soft',
  padding: false
});
```

## :computer: Code Examples

* tba

```javascript
images.forEach(image => {
  image.style.boxShadow = `10px 10px ${options.shadow_type} 1px rgba(0,0,0,0.12)`;

  if(options.padding) {
    image.style.padding = '1em';
  }
})
```

## :cool: Features

* can be imported into any javascript app

## :clipboard: Status & To-Do List

* Status: Working
* To-Do: develop into a useful engineering module

## :clap: Inspiration

* [Youtube Gary Simon: Writing & Publishing your First NPM Package!](https://www.youtube.com/watch?v=4zzbNac6f6Q)]

## :envelope: Contact

* Repo created by [ABateman](https://www.andrewbateman.org) - you are welcome to [send me a message](https://andrewbateman.org/contact)
