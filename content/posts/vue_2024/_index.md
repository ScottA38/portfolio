---
author: Scott Anderson
title: 'A Vue2 a (s)kill: 007 reasons to use Vue 2 in 2024'
type: post
---

# A Vue 2 a (s)kill? 007 reasons to use Vue 2 in 2024

'VueJS? Isn't that like React's ugly brother?' I hear you sigh, and tab over to YouTube.


This often-overlooked MVVM javascript framework is armed with a complement of powerful weapons, such as [slots](https://v2.vuejs.org/v2/guide/components-slots), [composables](https://vuejs.org/guide/reusability/composables) and even state management via [Pinia](https://pinia.vuejs.org/) (previously [vuex](https://vuex.vuejs.org/)). Recently, I started learning VueJS from scratch, here are my highlights:

## MVVM? Sounds like a vacuum cleaner from the 80s, right?

MVVM stands for Model, View, View-Model, which doesn't actually help much if you have never come across this terminology before. Let's break it down:

 - **Model**: The data, the stuff you need to drive an application. Messy, raw and unfiltered, us frontenders take it as it comes
 - **View**: The page or template which takes the final values from the ViewModel and actually presents them to the user. Primary concerns are layout and UI.
 - **View-Model**: A kind of go-between implemented between the Model and the View, which helps encapsulate all data transformations and computation requisite to put the data on the page. If the VM (View-Model) does it's job correctly, the view can simply say 'gimme' and the data will be presented on the page.

The underlying stateful design of the 'View-Model' within an MVVM framework allows for data-driven workflows, meaning that you avoid stagnant static pages with low interactivity, yet also avoid messy bugs that can come with non-stateful programming (i.e: performing interactions via pure JavaScript or jQuery).

Without further ado, let's jump into the our 'features of the day':

1) [slots](https://v2.vuejs.org/v2/guide/components-slots):

![Building Frame](/building_frame.gif)

Imagine you are working on a new apartment complex. As the builder, you might know the . but not the  It's the same with VueJS slots. Oftentimes, when creating a component for a frontend framework we can define the *basis* of the component will remain the same but there is some required *variance* of parts of the template. Specifically, there are sometimes elements of variance which cannot be anticipated by the design of the component template, and need to be defined by the parent component.


