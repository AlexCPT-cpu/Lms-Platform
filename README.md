#  LMS Platform: React, Next.js 13, Prisma, Stripe, Mux, Tailwind, MySQL

Key Features:


- Easily reorder chapter position with drag n’ drop
- Upload thumbnails, attachments and videos using UploadThing
- Video processing using Mux
- Mark Chapters as Completed or Uncompleted
- HLS Video player using Mux
- Progress Calculation of each Course
- Student Dashboard
- ORM using Prisma
- MySQL database using Planetscale
- Teacher mode
- Create new Courses
- Browse & Filter Courses
- Purchase Courses using Stripe
- Create new Chapters
- Rich text editor for chapter description
- Authentication using Clerk


### Setup .env file


```js

DATABASE_URL=
UPLOADTHING_SECRET=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
MUX_TOKEN_ID=
MUX_TOKEN_SECRET=
STRIPE_API_KEY=
NEXT_PUBLIC_APP_URL=http://localhost:3000
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_TEACHER_ID=
UPLOADTHING_APP_ID=


```