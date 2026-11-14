# Stride — Running Training Plan Builder

A simple, no-signup website for building your own running training plans.

- Create as many plans as you like, starting either blank or from a 5K, 10K, half marathon, or marathon template
- Click any day to set the workout type, distance, duration, pace or effort, and notes, and to mark it done
- Copy, move, clear, add, or delete weeks
- See weekly totals, a mileage chart, peak week, and progress
- Export and import plans as JSON, and print a plan

Plans are stored in Firebase (Firestore collection `shared`). Anyone with the link can view them. Only the owner can edit, after signing in with Google; the Firestore rules enforce this.

## Live site

https://jackflemingcodes.github.io/

Hosted with GitHub Pages from the `main` branch. To change the site, edit `index.html` and commit. Pages redeploys automatically.
