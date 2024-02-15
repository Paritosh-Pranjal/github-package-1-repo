# My package 

A simple node package 

## Install Instructions

run
1.npm install @paritosh-pranjal/my-package@1.1.1
2.create a my-package.d.ts inside src folder
your-project
├── src
│   ├── my-package.d.ts
│   ├── App.tsx
│   └── ...other files

3.Open my-package.d.ts and add the following content:
declare module '@paritosh-pranjal/my-package';

4. tsconfig.json:
     "include": ["src"]