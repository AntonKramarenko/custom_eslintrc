1.  # Setup Eslint from https://eslint.org/docs/latest/user-guide/getting-started

     npm install eslint --save-dev

        or

     yarn add eslint --dev

2. # Add in project file with name and copy rules from .eslintrc :

     .eslintrc

3. # Add scripts in package.json:

    "scripts": {
    ...

     "lint": "eslint -c .eslintrc --ext .js,.jsx .",

     "lint:fix": "npm run lint -- --fix"

    }

4. # Run lint:

     npm run lint

5. # Auto-fix lint warning:

     npm run lint:fix
