## Tasks Summary

### Task 0: Creating an Interface for a Student
- **Objective**: Create a `Student` interface and render a table with student information.
- **Files**: `task_0/js/main.ts`, `task_0/package.json`, `task_0/.eslintrc.js`, `task_0/tsconfig.json`, `task_0/webpack.config.js`
- **Requirements**:
  - Define a `Student` interface with `firstName`, `lastName`, `age`, and `location`.
  - Create two student variables and store them in an array.
  - Render a table displaying the first name and location of each student using Vanilla JavaScript.
  - Ensure no TypeScript errors and use TypeScript for all variables.

### Task 1: Building a Teacher Interface
- **Objective**: Create a `Teacher` interface with specific attributes.
- **Files**: `task_1/js/main.ts`, `task_1/webpack.config.js`, `task_1/tsconfig.json`, `task_1/package.json`
- **Requirements**:
  - Define a `Teacher` interface with `firstName`, `lastName`, `fullTimeEmployee`, `yearsOfExperience`, and `location`.
  - Allow adding any attribute to the `Teacher` object.
  - Ensure no TypeScript errors and use TypeScript for all variables.

### Task 2: Extending the Teacher Class
- **Objective**: Extend the `Teacher` interface to create a `Directors` interface.
- **Files**: `task_1/js/main.ts`
- **Requirements**:
  - Define a `Directors` interface that extends `Teacher` and includes `numberOfReports`.
  - Ensure no TypeScript errors.

### Task 3: Printing Teachers
- **Objective**: Write a function to print teacher names in a specific format.
- **Files**: `task_1/js/main.ts`
- **Requirements**:
  - Define a `printTeacher` function that returns the first letter of the first name and the full last name.
  - Create an interface for the function.

### Task 4: Writing a Class
- **Objective**: Create a `StudentClass` with specific methods.
- **Files**: `task_1/js/main.ts`
- **Requirements**:
  - Define a `StudentClass` with methods `workOnHomework` and `displayName`.
  - Use interfaces to describe the class and its constructor.
  - Ensure no TypeScript errors.

### Task 5: Advanced Types Part 1
- **Objective**: Create interfaces and classes for `Director` and `Teacher` with specific methods.
- **Files**: `task_2/js/main.ts`, `task_2/webpack.config.js`, `task_2/tsconfig.json`, `task_2/package.json`
- **Requirements**:
  - Define `DirectorInterface` and `TeacherInterface` with methods `workFromHome`, `getCoffeeBreak`, and specific tasks.
  - Create `Director` and `Teacher` classes implementing these interfaces.
  - Create a `createEmployee` function to return either a `Director` or `Teacher` instance based on salary.

### Task 6: Creating Functions Specific to Employees
- **Objective**: Write functions to check if an employee is a director and execute specific tasks.
- **Files**: `task_2/js/main.ts`
- **Requirements**:
  - Define `isDirector` function to check if an employee is a director.
  - Define `executeWork` function to call specific methods based on the employee type.

### Task 7: String Literal Types
- **Objective**: Create a string literal type and a function to teach classes.
- **Files**: `task_2/js/main.ts`
- **Requirements**:
  - Define a `Subjects` type allowing values `Math` or `History`.
  - Create a `teachClass` function to return specific strings based on the class type.

### Task 8: Ambient Namespaces
- **Objective**: Create interfaces, types, and use ambient namespaces for CRUD operations.
- **Files**: `task_3/js/main.ts`, `task_3/js/interface.ts`, `task_3/js/crud.d.ts`
- **Requirements**:
  - Define `RowID` type and `RowElement` interface.
  - Create ambient declarations for CRUD functions.
  - Use these types and functions in `main.ts`.

### Task 9: Namespace & Declaration Merging
- **Objective**: Use namespaces and declaration merging to extend interfaces and classes.
- **Files**: `task_4/package.json`, `task_4/tsconfig.json`, `task_4/js/subjects/Cpp.ts`, `task_4/js/subjects/Java.ts`, `task_4/js/subjects/React.ts`, `task_4/js/subjects/Subject.ts`, `task_4/js/subjects/Teacher.ts`
- **Requirements**:
  - Create a `Teacher` interface and `Subject` class in the `Subjects` namespace.
  - Use declaration merging to add attributes to the `Teacher` interface.
  - Create classes for `Cpp`, `React`, and `Java` with specific methods.

### Task 10: Brand Convention & Nominal Typing
- **Objective**: Create interfaces with brand properties and functions to sum credits.
- **Files**: `task_5/js/main.ts`, `task_5/package.json`, `task_5/webpack.config.js`, `task_5/tsconfig.json`
- **Requirements**:
  - Define `MajorCredits` and `MinorCredits` interfaces with brand properties.
  - Create `sumMajorCredits` and `sumMinorCredits` functions to sum credits.
