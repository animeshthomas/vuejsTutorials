# vuejsTutorials

This project is a basic introduction to using Vue.js, demonstrating how to bind data and use two-way data binding in a simple web application.

## Overview

This tutorial creates a small Vue.js application with a simple input field that is bound to a header text. As you type into the input field, the header text updates in real-time, showcasing Vue's reactive data binding.

## Prerequisites

To run this project, you only need a web browser and an internet connection to access the Vue.js library through a CDN.

## How It Works

The `index.html` file contains the following elements:

1. **HTML Structure**:
   - A `div` with an ID of `shopping-list` is used as the root element of the Vue instance.
   - An `h1` tag displays the value of the `header` property.
   - An `input` element uses Vue's `v-model` directive to create a two-way binding with the `header` data property.

2. **Vue Initialization**:
   - The Vue instance is created with `new Vue()`, targeting the `#shopping-list` element.
   - The `data` object has a `header` property with an initial value of `"Shopping List App"`.
   - The `v-model` directive binds the `input` field's value to the `header` property, enabling real-time updates.

3. **Result**:
   - When you load the HTML file in a browser, the `h1` displays the text "Shopping List App".
   - As you type in the input field, the text inside the `h1` tag updates instantly to match the input.

## Usage

1. Download or clone this repository.
2. Open the `index.html` file in a web browser.
3. Observe the initial header text.
4. Type into the input field and see the header update as you type.

## Key Concepts

- **Two-Way Data Binding**: The `v-model` directive binds the input field to the `header` data property, allowing changes in the input to automatically update the displayed text.
- **Reactivity**: Vue updates the DOM automatically when data changes, making it simple to create interactive web applications.

## Dependencies

- [Vue.js (via CDN)](https://unpkg.com/vue@2)

This project uses the Vue.js library directly from a CDN, so there is no need for additional setup or installation.
