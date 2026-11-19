# User Profile Formatter

A small JavaScript project that formats user profile information into readable summaries.

## Project Brief

This project is based on the [JavaScript User Profile Formatter project](https://roadmap.sh/projects/js-user-profile-formatter) from roadmap.sh.

## Features

- Formats a user's display name.
- Formats the user's location.
- Returns contact information.
- Checks whether the user's account is active.
- Creates a complete profile summary.

## Run the Project

Make sure Node.js is installed, then run:

```bash
node userFormat.js
```

## Example User

```js
{
    id: 42,
    firstName: 'Ava',
    lastName: 'Stone',
    email: 'ava@example.com',
    phone: null,
    address: {
        city: 'London',
        country: 'UK',
    },
    account: {
        status: 'active',
        plan: 'pro',
    },
}
```

## Concepts Practiced

- JavaScript functions
- Template literals
- Objects and nested objects
- Conditional values with `||`
- Returning formatted data
