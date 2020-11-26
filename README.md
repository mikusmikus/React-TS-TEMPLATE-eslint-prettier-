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

