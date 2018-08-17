#Easiest React Redux Demo with little UI state managment like tab, input, select, checkbo, radio

Purpose of this demo is to understand redux easily. You can find step by step guide here to understand this demo properly.

##React Redux configuration

First install `react-redux`
```
npm install react-redux --save

```

Now, you need to define provider and store in index.js

```
import { Provider } from 'react-redux';
import { store } from './reducers';

ReactDOM.render(
    <Provider store={store}>
        <App />
    </Provider>,
    document.getElementById('root')
);

Now, we need to create two files :

    1) action/index.js
    2) reducers/index.js

1) action/index.js

```
