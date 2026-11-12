# React Lab Exercise 1: Understanding React File Structure
## Name: LOGESH S
## Roll no: 2305001014
## Department: CSE

## AIM
### To create a React application using Vite, understand its file structure, and develop reusable components.

## PROGRAM


### i) Student.jsx
```css
function Student() {
 return (
 <div>
 <h2>Student Details</h2>
 <p>Name: Aravindan T</p>
 <p>Register Number: 2305001003</p>
 <p>Department: CSE</p>
 </div>
 );
}
export default Student;
```
### ii) Course.jsx
```css
function Course() {
 return (
 <div>
 <h2>Course Details</h2>
 <p>Course: Web Technology</p>
 <p>Semester: VII</p>
 <p>Credits: 4</p>
 </div>
 );
}
export default Course;
```

### iii) Faculty.jsx
```c
function Faculty() {
 return (
 <div>
 <h2>Faculty Details</h2>
 <p>Name: Dr. Ajith Kumar</p>
 <p>Department: AIDS</p>
 <p>Designation: Professor</p>
 </div>
 );
}
export default Faculty;
```

### iv) App.jsx
```css
import Student from "./components/Student";
import Course from "./components/Course";
import Faculty from "./components/Faculty";
import "./App.css";
function App() {
 return ( <div className="container">
 <h1>Student Information System</h1>
 <Student />
 <Course />
 <Faculty />
 </div>
 );
}
export default App;
```

### v) App.css
```css
.container {
 text-align: center;
 padding: 30px;
 font-family: Arial, sans-serif;
}
.container h1 {
 color: #1976d2;
}
.container h2 {
 color: #333333;
}
.container p {
 color: #555555;
 font-size: 16px;
}
.container > div {
 border: 1p
x solid #cccccc;
 border-radius: 8px;
 padding: 20px;
 margin: 20px auto;
 max-width: 300px;
 background-color: #f5f9ff;
}
```
## OUTPUT
<img width="995" height="344" alt="image" src="https://github.com/user-attachments/assets/8f8a9446-fefe-42d4-a61c-de72a2ff06ef" />
<img width="1005" height="522" alt="image" src="https://github.com/user-attachments/assets/2583cac9-b6a8-4cd4-9334-cdc85651e800" />

## RESULT
### Thus, the Student Information System was successfully created using React components for student, course, and faculty details.
