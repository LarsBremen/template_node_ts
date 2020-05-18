# template_node_ts
Template for node projects including configuration for Typescript and eslint 
as well as mocha and chai for testing.

## First steps
Go to the package.json and change the parameters, `name`, `repository->url`,
`bugs->url` and `homepage` according to your new project name and your new
repository.  

## Build and Run
`npm run build` compiles the app to js.  
`npm run start` executes the compiled code.  
`npm run serve` runs the app with ts-node.  

## Test
Test should be placed in `./spec` and every test file needs to end with `.spec.ts`.  
`npm run test` will run the tests.  
`npm run lint` runs eslint.
