# Phone book contact storage app

- The goit-react-hw-02-phonebook repository has been created.
- There is a separate file for each component in the src/components folder.
- For components, propTypes are described.
- Everything that the component expects in the form of props is passed to it when it is called.
- Styling is done by CSS Modules.

The application consists of a form and a list of contacts.

Implementing adding of contact name and displaing a list of contacts.

The application doesn't save contacts between different sessions (page refresh). 

Each contact is an object with `name` and `id` properties.

`Nanoid` is used to generate identifiers.

User can add or delete contacts from contact book.

For the contact searching search field was realized, filtration logics is case insensitive.

The user cannot add contacts whose names are already in the phone book.
If you try to perform this action, a warning is displayed.
