[![Version](https://vsmarketplacebadge.apphb.com/version-short/walter-ribeiro.full-react-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=walter-ribeiro.full-react-snippets)
[![Install](https://vsmarketplacebadge.apphb.com/installs-short/walter-ribeiro.full-react-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=walter-ribeiro.full-react-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating-short/walter-ribeiro.full-react-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=walter-ribeiro.full-react-snippets)

<!-- TABLE OF CONTENTS -->

# Table of Contents

- [Usage](#usage)
- [Snippets List](#snippets-list)
  - [ES7](#eS7)
  - [GraphQL](#graphQL)
  - [PropTypes](#proptypes)
  - [HOC](#hOC)
  - [React Native](#react-native)
  - [React](#react)
  - [Redux](#redux)
  - [React Router](#react-router)
  - [Testing](#testing)
  - [Hooks](#hooks)  
  - [Reactotron](#reactotron)  
  - [Styled Components](#styled-components)  
  - [Others](#others)  
- [License](#license)
- [Contact](#contact)


## Usage

After install this snippets add this inside your settings

`"editor.snippetSuggestions": "top",`

## Snippets List

### ES7

| Snippets | Content                 |
| -------: | ----------------------- |
|      edl | Eslint Disable Line     |
|     imst | Import Statement        |
|      imp | Import                  |
|      imn | Import No Module Name   |
|      ime | Import Everything       |
|      ima | Import As               |
|       ed | Export Default          |
|      exd | Export Destructing      |
|      exa | Export As               |
|      enf | Export Named Function   |
|      edf | Export Default Function |
|      met | Method                  |
|      fre | For Each                |
|      fof | For Of                  |
|      fin | For Inf                 |
|     anfn | Anonymous Function      |
|      nfn | Named Function          |
|      dob | Destructing Object      |
|      dar | Destructing Array       |
|      sti | Set Interval            |
|      sto | Set TimeOut             |
|     prom | Promise                 |
|      cas | Console Assert          |
|      ccl | Console Clear           |
|      cco | Console Count           |
|      cdi | Console Dir             |
|      cer | Console Error           |
|      cgr | Console Group           |
|      cge | Console Group End       |
|      clg | Console Log             |
|      ctr | Console Trace           |
|      cwa | Console Warn            |
|      cin | Console Info            |
|       cm | Comment Block           |
|     cmmb | Comment Big Block       |
|      cbl | Comment Big Line        |

### GraphQL

| Snippets | Content               |
| -------: | --------------------- |
|  graphql | GraphQL For Component |
|   expgql | Export GraphQL        |

### PropTypes

| Snippets | Content                        |
| -------: | ------------------------------ |
|     impt | Import PropTypes               |
|      pta | Prop Type Array                |
|     ptar | Prop Type Array Required       |
|      ptb | Prop Type Bool                 |
|     ptbr | Prop Type Bool Required        |
|      ptf | Prop Type Func                 |
|     ptfr | Prop Type Func Required        |
|      ptn | Prop Type Number               |
|     ptnr | Prop Type Number Required      |
|      pto | Prop Type Object               |
|     ptor | Prop Type Object Required      |
|      pts | Prop Type String               |
|     ptsr | Prop Type String Required      |
|     ptnd | Prop Type Node                 |
|    ptndr | Prop Type Node Required        |
|     ptel | Prop Type Element              |
|    ptelr | Prop Type Element Required     |
|      pti | Prop Type Instance Of          |
|     ptir | Prop Type Instance Of Required |
|      pte | Prop Type Enum                 |
|     pter | Prop Type Enum Required        |
|     ptet | Prop Type One Of Type          |
|    ptetr | Prop Type One Of Type Required |
|     ptao | Prop Type Array Of             |
|    ptaor | Prop Type Array Of Required    |
|     ptoo | Prop Type Object Of            |
|    ptoor | Prop Type Object Of Required   |
|     ptsh | Prop Type Shape                |
|    ptshr | Prop Type Shape Required       |
|   ptypes | Static Prop Types              |

### HOC

| Snippets | Content        |
| -------: | -------------- |
| hocredux | HOC With Redux |
|      hoc | HOC            |

### React Native

| Snippets | Content                                     |
| -------: | ------------------------------------------- |
|      rnc | React Native Component                      |
|     rnce | React Native Component Export               |
| rncredux | React Native Class Component Redux          |
|     rnfc | React Native Functional Component **`New`** |
|     imrn | React Native Import                         |
|  rnstyle | React Native Style **`New`**                |

### React

| Snippets | Content                                                        |
| -------: | -------------------------------------------------------------- |
|      imr | Import React                                                   |
|     imrc | Import React, { Component }                                    |
|    imrcp | Import React, { Component } & PropTypes                        |
|    imrpc | Import React, { PureComponent }                                |
|   imrpcp | Import React, { PureComponent } & PropTypes                    |
|      rcc | React Class Compoment                                          |
|      rce | React Class Export Component                                   |
|      rfe | React Functional Export Component                              |
|     rfep | React Functional Export Component With PropTypes               |
|      rfc | React Functional Component **`Updated`**                       |
|     rfcp | React Functional Component With PropTypes **`Updated`**        |
|     rcep | React Class Export Component With PropTypes                    |
|      rpc | React Class Pure Component                                     |
|     rpcp | React Class Pure Component With PropTypes                      |
|     rccp | React Class Compoment PropTypes                                |
|   rconst | Class Constructor                                              |
|      est | Empty State                                                    |
|     dsfp | Get Derived State From Props                                   |
|      sbu | Get Snapshot Before Update                                     |
|      cdc | Component Did Catch                                            |
|      cdm | Component Did Mount                                            |
|     cdma | Component Did Mount (Arrow func)                               |
|      scu | Should Component Update                                        |
|     scua | Should Component Update (Arrow func)                           |
|     cdup | Component Did Update                                           |
|    cdupa | Component Did Update (Arrow func)                              |
|     cwun | Component Will Unmount                                         |
|    cwuna | Component Will Unmount (Arrow func)                            |
|      cwm | Component Will Mount ***[Deprecated]***                        |
|     cwma | Component Will Mount (Arrow func) - ***[Deprecated]***         |
|      cwr | Component Will Receive Props ***[Deprecated]***                |
|     cwra | Component Will Receive Props (Arrow func) - ***[Deprecated]*** |
|     cwup | Component Will Update ***[Deprecated]***                       |
|    cwupa | Component Will Update (Arrow func) - ***[Deprecated]***        |
|      ren | Component Render                                               |
|      sst | Component Set State Object                                     |
|      ssf | Component Set State Func                                       |
|    props | Component Props                                                |
|    state | Component State                                                |

### Redux

|  Snippets | Content                     |
| --------: | --------------------------- |
|     redux | Import Redux Statement      |
|       rpf | Redux Pure Function         |
|       rpc | Redux Pure Function Const   |
|   rcredux | React Class Compoment Redux |
|  reduxmap | Mapping To Props            |
|  rxaction | Redux Action                |
|   rxconst | Redux Const                 |
| rxreducer | Redux Reducer               |
|  rxselect | Redux Selector              |

### React Router

| Snippets | Content                                                           |
| -------: | ----------------------------------------------------------------- |
|     imrr | import { BrowserRouter as Router, Route } from 'react-router-dom' |
|     imnl | import { NavLink } from 'react-router-dom'                        |
|     imwr | import { withRouter } from 'react-router'                         |
|   router | react-router Router template                                      |
|    route | react-router Route component                                      |
|  navlink | react-router NavLink component                                    |

### Testing

| Snippets | Content                            |
| -------: | ---------------------------------- |
|     desc | Describe Block                     |
|     test | Test Block                         |
|      tit | It Block                           |
|    stest | Setup Test                         |
|   sjtest | Setup Test With Enzyme To Json     |
|   sntest | Setup React Native Test            |
|  snrtest | Setup React Native Test With Redux |

### Hooks

|            Snippets | Content                  |
| ------------------: | ------------------------ |
|            useState | useState Hook            |
|           useEffect | useEffect Hook           |
|          useContext | useContext Hook          |
|          useReducer | useReducer Hook          |
|         useCallback | useCallback Hook         |
|             useMemo | useMemo Hook             |
|              useRef | useRef Hook              |
| useImperativeHandle | useImperativeHandle Hook |
|     useLayoutEffect | useLayoutEffect Hook     |
|       useDebugValue | useDebugValue Hook       |

### Reactotron

|      Snippets | Content                                            |
| ------------: | -------------------------------------------------- |
|        tron-r | Reactotron Config React **`New`**                  |
|  tron-redux-r | Reactotron Redux Config for React **`New`**        |
|       tron-rn | Reactotron Config for React Native **`New`**       |
| tron-redux-rn | Reactotron Redux Config for React Native **`New`** |
|           ctl | Reactotron Console Log **`New`**                   |
|           ctw | Reactotron Console Warn **`New`**                  |
|           cte | Reactotron Console Error **`New`**                 |

### Styled Components

|  Snippets | Content                                           |
| --------: | ------------------------------------------------- |
|  styled-r | Styled Components File for React **`New`**        |
| styled-rn | Styled Components File for React Native **`New`** |
|       stc | Styled Component **`New`**                        |

### Others

|     Snippets | Content                    |
| -----------: | -------------------------- |
|          api | Axios API **`New`**        |
| root-reducer | Root Reducer **`New`**     |
|    root-saga | Root Saga **`New`**        |
|    root-saga | Root Saga **`New`**        |
|         duck | Duck **`New`**             |
|       rsduck | Redux Sauce Duck **`New`** |
|           cs | Create Store **`New`**     |


## License

Distributed under the MIT license. See `LICENSE` for more information.

## Contact

Walter Ribeiro - [Github](https://github.com/walteribeiro) - **walterjunioranalise@gmail.com**
