  REACT/TS TEMPLATE  (Prettier-ESlint formatter)
  
    import React, { useState, useEffect } from 'react';
    import * as _ from 'lodash';
    import 'flexboxgrid';
    import axios from 'axios';
    import {
    BrowserRouter as Router,
    Switch,
    Route,
    Link,
    Redirect,
    } from 'react-router-dom';
    import { v4 as uuidv4 } from 'uuid';
    import 'bootstrap/dist/css/bootstrap.min.css';
    import { ToastContainer, toast } from 'react-toastify';
    import 'react-toastify/dist/ReactToastify.css';
    import { useBottomScrollListener } from 'react-bottom-scroll-listener'
    import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
    import { icon } from '@fortawesome/free-solid-svg-icons'   
  
  "dependencies": {
    "@fortawesome/fontawesome-free": "^5.15.1",
    "@testing-library/jest-dom": "^5.11.5",
    "@testing-library/react": "^11.1.1",
    "@testing-library/user-event": "^12.2.0",
    "@types/jest": "^26.0.15",
    "@types/lodash": "^4.14.165",
    "@types/node": "^12.19.3",
    "@types/react": "^16.9.55",
    "@types/react-dom": "^16.9.9",
    "@types/react-router-dom": "^5.1.6",
    "@types/uuid": "^8.3.0",
    "axios": "^0.21.0",
    "bootstrap": "^4.5.3",
    "flexboxgrid": "^6.3.1",
    "gh-pages": "^3.1.0",
    "lodash": "^4.17.20",
    "node-sass": "^4.14.1",
    "react": "^17.0.1",
    "react-bootstrap": "^1.4.0",
    "react-bottom-scroll-listener": "^4.1.1",
    "react-dom": "^17.0.1",
    "react-lodash": "^0.1.2",
    "react-router-dom": "^5.2.0",
    "react-scripts": "4.0.0",
    "react-toastify": "^6.1.0",
    "typescript": "^4.0.5",
    "uuid": "^8.3.1",
    "web-vitals": "^0.2.4"
  },


ja ir uztaisīts aps, bet nav ielikts repositorijā, tad daram tā: 
1. uztaisi jaunu repository githubā

2. atveram appu VSC, tad atveram  SOURCE CONTROL, tad add remote uz repository. ...-> Remote-> addRemote -> pievienojam izveidoto repp
https://gyazo.com/441d1662710d8bf366898e78bb9ccb72

3. commit changes 
https://gyazo.com/2159295ba4a9508c6ab0f9d12c5cd277

4. ... -> push
https://gyazo.com/74d5f60f9c8929da52aa1ea6ef5f05c2


ja gribam update repository pēc kkādām izmaiņām appā.
1. commit changes
2. ... -> push



lai deployotu @gh-pages

1. iekš  package.json
"homepage": "http://{github-name}.github.io/{repository-name}"
"homepage": "http://mikusmikus.github.io/animal-animal"

2. commit changes
3. ... -> push

4. terminālī =>>>>>>>>  npm run deploy 

5. Pēctam dodas uz gh-> savu repository -> settings -> tinot uz leju būs links uz app interneta page (pēc deploy ~5min laikā sāks strādāt)