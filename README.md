# RWAP
Ride With a Pro website for better flow on FND nights

> ⚠️ **Superseded prototype — do not use on event nights.**
>
> These pages store everything in the browser's `localStorage` on whatever
> device they are opened on. Nothing is sent to a server, so:
>
> - Customer sign-ups made on a customer's phone **never reach the staff
>   device** — each device only sees its own data.
> - Rides logged by staff are saved locally but are **not shown anywhere in
>   the UI** and there is no export, so they appear to vanish.
> - Clearing browser data (or private browsing) deletes everything.
>
> Use the current app instead: **[rwap-awesome](https://github.com/Donnini3/rwap-awesome)**
> (React + Supabase), which persists submissions to a shared database with
> a live feed, stats, and CSV export.
