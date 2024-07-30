## Liveblocks & Cooperative Editor

### Cooperative Editor is a clone of Google Docs. 

#### The primary goal is to demonstrate the developer's skills in realtime environment that creates a lasting impact.


[SITE](https://liveblocks-cooperative-editor-sxidsvit.vercel.app/)

![](demo.gif)


### Tech Stack

- Next.js 14
- TypeScript
- [Liveblocks](https://liveblocks.io/) - is a comprehensive platform that empowers developers to seamlessly create, deploy, and scale real-time collaborative applications
- [Clerk](https://clerk.com/) - the most comprehensive User Management Platform
- Lexical Editor
- ShadCN
- Tailwind CSS
- [Sentry](https://sentry.io/) - an application monitoring software considered "not bad" by 4 million developers

### Features

 **Authentication**: User authentication using GitHub through NextAuth, ensuring secure sign-in/out and session management.

 **Collaborative Text Editor**: Multiple users can edit the same document simultaneously with real-time updates.

 **Documents Management**
  - **Create Documents**: Users can create new documents, which are automatically saved and listed.
  - **Delete Documents**: Users can delete documents they own.
  - **Share Documents**: Users can share documents via email or link with view/edit permissions.
  - **List Documents**: Display all documents owned or shared with the user, with search and sorting functionalities.

 **Comments**: Users can add inline and general comments, with threading for discussions.

 **Active Collaborators on Text Editor**: Show active collaborators with real-time presence indicators.

 **Notifications**: Notify users of document shares, new comments, and collaborator activities.

 **Responsive**: The application is responsive across all devices.



**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/collaborative-editor.git 
cd liveblocks-cooperative-editor
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

```env
#Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

#Liveblocks
LIVEBLOCKS_SECRET_KEY=

#Sentry
SENTRY_AUTH_TOKEN=
```

Replace the placeholder values with your actual Clerk & LiveBlocks credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/) and [Liveblocks](liveblocks.io/) website.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.


---

##### Contact with me:

[<img alt="webDev | LinkedIn" src="https://img.shields.io/badge/linkedin-0077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />][linkedin]

[linkedin]: https://www.linkedin.com/in/sergiy-antonyuk/

##### I can't express how much I have learned from [you](https://www.youtube.com/@javascriptmastery) ! <br> Thanks for the hard and smart work.
