```jsx
// This file is named: `Container.jsx` in Qualified

// SOLUTION FILE

import React from "react";

const Container = (props) => {
  return <div>{props.children}</div>;
};

export default Container;
```

---

```jsx
// This file is named: `IdCard.jsx` in Qualified

// SOLUTION FILE

import React from "react";

const IdCard = ({ fullName, gender, birthday, picture }) => {
  return (
    <section style={{ border: "2px solid black", padding: "10px", marginBottom: "10px" }}>
      <p>
        <b>Full Name:</b> {fullName}
      </p>
      <p>
        <b>Gender:</b> {gender}
      </p>
      <p>
        <b>Birthdate:</b> {birthday}
      </p>
      <img src={picture} alt='profile-pic' />
    </section>
  );
};

export default IdCard;
```

---

```jsx
// SOLUTION FILE

import React from "react";

import Container from "./Container";
import IdCard from "./IdCard";

function App() {
  return (
    <div>
      <Container>
        <IdCard
          fullName='John Doe'
          gender='male'
          birthday='1992-07-14'
          picture='https://randomuser.me/api/portraits/men/44.jpg'
        />
        <IdCard
          fullName='Obrien Delores'
          gender='female'
          birthday='1988-05-11'
          picture='https://randomuser.me/api/portraits/women/44.jpg'
        />
      </Container>
    </div>
  );
}

export default App;
```
