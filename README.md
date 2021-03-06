# React / Redux
:link: *[w6d5](#w6d5) :: [w7d1](#w7d1) :: [w7d2](#w7d2) :: [w7d3](#w7d3)
:: [w7d4](#w7d4) :: [w7d5](#w7d5) :: [w8d1](#w8d1) :: [w8d2](#w8d2)*
:link:

## w6d5

### :clock10: Class will start at 10am! :clock10:
- **Progress Tracker reports are still due at 9am.**

### Readings (63 min)
**Tonight only, please do the readings before watching the video
lectures**
- [NPM][npm_configuration] (15 min)
- [Webpack][webpack_configuration] (10 min)
- [ES6 Syntax: Object Destructuring][object_destructuring] (10 min)
- [ES6 Syntax: Import / Export][import_export] (10 min)
- [React Developer Tools][react_dev_tools] (3 min)
- [Thinking in React][thinking_in_react] (15 min)

[npm_configuration]: readings/npm_configuration.md
[webpack_configuration]: readings/webpack_configuration.md
[import_export]: readings/import_export.md
[object_destructuring]: readings/object_destructuring.md
[react_dev_tools]: readings/react_dev_tools.md
[thinking_in_react]: https://facebook.github.io/react/docs/thinking-in-react.html

### Video Lectures (68 min)
:closed_lock_with_key: `go_video_go`
* :movie_camera: [React: Intro][react-intro] (27 min)
* :movie_camera: [React: Transpilation][react-transpilation] (8 min)
* :movie_camera: [React: Functional Components][react-func-comps] (22 min)
* :movie_camera: [React: Lifecycle Methods][react-lifecycle] (11 min)
  * :computer: [code from click counter demo][click-demo]

[react-intro]: https://vimeo.com/188074204
[react-transpilation]: https://vimeo.com/188087366
[react-func-comps]: https://vimeo.com/188090786
[react-lifecycle]: https://vimeo.com/188093789

### Homeworks (75 min)
- [Getting Started with NPM][getting_started] (30 min)
- [React Calculator][react_calculator] (45 min)

[getting_started]: homeworks/getting_started
[react_calculator]: homeworks/calculator

### Additional Resources
- [Babel][babel_configuration]
- [React][intro_to_react]
- [JSX][intro_to_jsx]
- [React Components][intro_to_react_components]
- [Declaration][component_declaration]
- [Props and State][props_and_state]
- [Lifecycle Methods][component_lifecycle]
- [Synthetic Events][synthetic_events]
- [Official React Documentation][react_docs]
  - Most Helpful: REFERENCE Section (Left Sidebar)

### Projects
- [Widgets][widgets]
- [Minesweeper][minesweeper]

[widgets]: projects/widgets
[minesweeper]: projects/react_minesweeper

[click-demo]: demos/click-counter

[npm_configuration]: readings/npm_configuration.md
[webpack_configuration]: readings/webpack_configuration.md
[babel_configuration]: readings/babel_configuration.md
[intro_to_react]: readings/intro_to_react.md
[intro_to_jsx]: readings/intro_to_jsx.md
[intro_to_react_components]: readings/intro_to_react_components.md
[props_and_state]: readings/props_and_state.md
[component_declaration]: readings/component_declaration.md
[component_lifecycle]: readings/component_lifecycle.md
[synthetic_events]: readings/synthetic_events.md
[react_docs]: https://facebook.github.io/react/docs/getting-started.html

## w7d1

### Readings (140 min)
- [Lodash][lodash] (5 min)
- [Flux and Redux Intro][flux_redux] (10 min)
- [Store][store] (20 min)
- [Reducers][reducers] (20 min)
- [Actions][actions] (10 min)
- [`<Provider/>`][provider] (15 min)
- [`connect()`][connect] (15 min)
- [Containers][containers] (10 min)
- [Selectors][selectors] (10 min)
- [Nontechnical Overview of React][react-nontech] (15 min)

[lodash]: readings/lodash.md
[store]: readings/store.md
[reducers]: readings/reducers.md
[actions]: readings/actions.md
[flux_redux]: readings/flux_redux.md
[provider]: readings/provider.md
[connect]: readings/connect.md
[containers]: readings/containers.md
[selectors]: readings/selectors.md
[react-nontech]: readings/react_nontech.md

### Fruit Stand App Demo (120 min)
+ Phase I - Redux only (15 min)
  + [Live demo][fruit-stand-01-live]
  + :computer: [Source code][fruit-stand-01-source]
+ Phase II - React/Redux (1 hr)
  + :movie_camera: [Video demo][fruit-stand-02-video]
:closed_lock_with_key: `go_video_go` (45 min)
  + [Live demo][fruit-stand-02-live]
  + :computer: [Source code][fruit-stand-02-source]

[fruit-stand-01-live]: http://appacademy.github.io/curriculum/react/fruit_stand_01/index.html
[fruit-stand-01-source]: ./demos/fruit_stand_demos/fruit_stand_01
[fruit-stand-02-video]: https://vimeo.com/184374712
[fruit-stand-02-live]: http://appacademy.github.io/curriculum/react/fruit_stand_02/index.html
[fruit-stand-02-source]: ./demos/fruit_stand_demos/fruit_stand_02

### Homeworks (45 min)
- [Dollar Store][dollar_store_hw] (45 min)

[dollar_store_hw]: homeworks/dollar_store

### Additional Resources
- [Official `redux` Documentation][redux_docs]
- [Official `react-redux` Documentation][react_redux_docs]
  - *Note: The 'API' sections are especially useful.*

[redux_docs]: http://redux.js.org/index.html
[react_redux_docs]: https://github.com/reactjs/react-redux/blob/master/docs/

### Projects
- [Todos][todos]

## w7d2

### Readings (60 min)
- [Higher-order Functions][higher_order_functions] (15 min)
- [Middleware][middleware] (15 min)
- [Thunks][thunks] (15 min)
- [Object.freeze][obj-freeze] (10 min)
- [Namespacing][namespacing] (5 min)

[higher_order_functions]: readings/higher_order_functions.md
[middleware]: readings/middleware.md
[thunks]: readings/thunks.md
[obj-freeze]: readings/object_freeze.md
[namespacing]: readings/rails_router_namespacing.md

### Homework (45 min)
- [Middleware Homework][middleware_homework] (45 min)

[middleware_homework]: homeworks/middleware

### Projects
- Continue [Todos][todos]

[todos]: projects/todos

## w7d3

### Study Hall 9 - 10am

### Readings (50 min)
- [Intro to Jbuilder][jbuilder-intro] (5 min)
- [Jbuilder][jbuilder_docs] (20 min)
- Normalizing Redux State Shape (from Redux docs)
  - [Normalizing State Shape][normalizing] (5 min)
  - [Updating Normalized Data][updating-normalized] (5 min)
- [Nontechnical Overview of Redux][redux-nontech] (15 min)

[jbuilder-intro]: readings/intro_to_jbuilder.md
[jbuilder_docs]: https://github.com/rails/jbuilder
[normalizing]: http://redux.js.org/docs/recipes/reducers/NormalizingStateShape.html
[updating-normalized]: http://redux.js.org/docs/recipes/reducers/UpdatingNormalizedData.html
[redux-nontech]: readings/redux_nontech.md

### Homeworks (100 min)
- [Giphy Homework][giphy_homework] (90 min)
- [Submit your tentative full-stack project
proposal][tentative-proposal] (10 min)
  - **Due by 9AM Thursday w7d4**
  - You may want to browse our [list of approved apps][approved-apps]

[giphy_homework]: homeworks/giphy
[tentative-proposal]: ../full-stack-project/proposal/tentative-project-proposal.md
[approved-apps]: ../full-stack-project/proposal/projects-to-clone.md

### Additional Resources
- [Redux Developer Tools][redux_dev_tools]

[redux_dev_tools]: readings/redux_dev_tools.md

### Projects
- [Jbuilder][jbuilder_exercise]
- [Pokedex][pokedex]

[jbuilder_exercise]: projects/jbuilder
[pokedex]: projects/pokedex

## w7d4

### Readings (26 min)
- [Intro to React Router][react_router_intro]  (15 min)
- [`<Link>`][link] (5 min)
- [`<Switch>`][switch] (2 min)
- [`withRouter`][with_router] (2 min)
- [`<Redirect>`][redirect] (2 min)

[react_router_intro]: readings/intro_to_react_router.md
[link]: readings/link.md
[switch]: readings/switch.md
[with_router]: readings/with_router.md
[redirect]: readings/redirect.md

### Homeworks (40 min)
- [Submit your tentative full-stack project proposal][tentative-proposal] (10 min)
- [Rainbow Routes][rainbow_routes] (30 min)

[rainbow_routes]: homeworks/rainbow_routes

### Additional Resources
- [React Router docs](https://reacttraining.com/react-router/web/guides/quick-start)

### Projects
* Continue [Pokedex][pokedex]

[react_router_docs]: https://github.com/reactjs/react-router/blob/v3/docs/

## w7d5

### Video Lectures (44 min)
:closed_lock_with_key: `go_video_go`
* :movie_camera: [Intro to UI/UX][uiux-intro] (4 min)
* :movie_camera: [Intro to UX for Web][uiux-web] (6 min)
* :movie_camera: [UI Affordances and Signifiers][uiux-affordances] (4 min)
* :movie_camera: [Designing to Look Good][uiux-look-good] (11 min)
* :movie_camera: [Frontend Auth: Intro][frontend_auth_1] (2 min)
* :movie_camera: [Frontend Auth: API Authentication][frontend_auth_2] (3 min)
* :movie_camera: [Frontend Auth: Frontend Auth Pattern][frontend_auth_3] (14 min)

[uiux-intro]: https://vimeo.com/album/4453315/video/206661754
[uiux-web]: https://vimeo.com/album/4453315/video/206661769
[uiux-affordances]: https://vimeo.com/album/4453315/video/206661839
[uiux-look-good]: https://vimeo.com/album/4453315/video/206661864
[frontend_auth_1]: https://vimeo.com/210683007
[frontend_auth_2]: https://vimeo.com/210683951
[frontend_auth_3]: https://vimeo.com/210684312


### Readings (20 min)
- [`preloadedState`][preloaded_state] (5 min)
- [Front End Authentication][user_authentication] (15 min)

[preloaded_state]: readings/preloaded_state.md
[user_authentication]: readings/front_end_auth.md

### Homeworks (60/75 min)
* Do the auth part of [A04 Prep][a04_prep] (60 min)
  * Front-end auth (the main concept in BenchBnB Day 1) builds on top of regular Rails backend auth, so make sure you build on a solid base.
  * You'll be surprised how much of it you've forgotten by now. It's normal.

[a04_prep]: https://github.com/appacademy/assessment-prep#assessment-4

### Additional Resources
- [Rails/React/Redux Configuration Checklist][checklist]
- [React Context][context]
- [`localStorage`][local_storage]

[checklist]: readings/checklist.md
[context]: https://facebook.github.io/react/docs/context.html
[local_storage]: https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage

### Projects
- [BenchBnB][bench_bnb]

[bench_bnb]: projects/bench_bnb

## w8d1

**Project Proposal Review Period for Instructional Staff**

### Readings (25 min)
-	[React Map Demo][react_map_demo] (15 min)
- **(Review)** [Thinking in React][thinking_in_react] (10 min)

[react_map_demo]: demos/react_map_demo


### Homework (5.5 hrs)
* [UX/UI Layout Practice][uxhw] (30 min)
* Submit your [full-stack project proposal][full_stack_project_proposal] (5 hrs)
  * **Due by 9am on Monday w8d1**

[full_stack_project_proposal]: ../full-stack-project/proposal/full-stack-project-proposal.md
[uxhw]: ../full-stack-project/homeworks/ux

### Additional Resources
* See [full-stack project curriculum][full_stack_project_curriculum] for additional information and readings related to full-stack projects.

[full_stack_project_curriculum]: ../full-stack-project

### Projects
* **Solo:** Continue [BenchBnB][bench_bnb]

## w8d2

### Homework
* Begin work on projects
