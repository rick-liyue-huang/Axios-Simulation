## Using TypeScript Simulate Axios Framework

## Features
1. Using XMLHttpRequest on browser end;
2. Support Promise API;
3. Support request and response interrupter;
4. Support request data and response data format transformation;
5. Support request cancellation;
6. Support JSON data transformation automatically;
7. Support client end XSS attacking.


## Simulation Axios framework Structure
```markdown
-- src
|   |-- axios.ts
|   |-- defaults.ts
|   |-- index.ts
|   |-- cancel
|   |   |-- Cancel.ts
|   |   |-- CancelToken.ts
|   |-- core
|   |   |-- Axios.ts
|   |   |-- InterceptorManager.ts
|   |   |-- dispatchRequest.ts
|   |   |-- mergeConfig.ts
|   |   |-- transform.ts
|   |   |-- xhr.ts
|   |-- helpers
|   |   |-- cookie.ts
|   |   |-- data.ts
|   |   |-- error.ts
|   |   |-- headers.ts
|   |   |-- url.ts
|   |   |-- util.ts
|   |-- types
|       |-- index.ts

```

### Example Usage

After running the project, it will show the multiple links, each of which to test the axios simulation is working by checking the console, and each link match the subdirectory name. 

clone or download the project, run `npm i` to install dependencies, and run `npm run dev` to open the local project on 'http://localhost:8080' to see the project display.
![avatar](/project-display.png)

