# Construction Task Dashboard

An interactive, mobile-responsive task management dashboard for construction projects with GitHub integration.

## Features

✅ **Dual Access Modes**
- **Guest Mode**: View-only access for team members
- **Admin Mode**: Full edit capabilities with add/edit/delete tasks

✅ **Smart Filtering**
- Filter by area (Prasadam Hall, Ashram, STP, Road, Temple, Structural)
- Filter by priority (High, Medium, Low)
- Filter by status (Completed, Pending, In Progress)
- Filter by specific date

✅ **Mobile-Responsive Design**
- Optimized for all screen sizes
- Touch-friendly interface
- Adaptive layout for phones and tablets

✅ **Real-time Statistics**
- Total tasks counter
- Pending tasks tracker
- Completed tasks count
- Overdue tasks alert

✅ **Task Management**
- Add new tasks
- Edit existing tasks
- Delete tasks
- Track deadlines and priorities
- Add notes to tasks

## Usage

### Guest Mode
1. Open the dashboard
2. View all tasks across different construction areas
3. Use filters to find specific tasks
4. Check deadlines and priorities

### Admin Mode
1. Click "Switch to Admin" in the header
2. Edit tasks by clicking the "Edit" button on any task card
3. Delete tasks with the "Delete" button
4. Add new tasks using "+ Add Task" button
5. Sync changes to GitHub with "💾 Sync to GitHub" button

## Local Setup

1. Clone this repository
2. Open `index.html` in your browser
3. Tasks are stored in `tasks-data.json`

## Data Structure

Tasks are organized by construction areas:
- PRASADAM HALL
- ASHRAM / BRAHMACHARI AREA
- STP & PUBLIC TOILET
- ROAD (PAVER AREA)
- TEMPLE AREA
- STRUCTURAL / GRC WORK

Each task contains:
- Task title
- Current status
- Deadline
- Priority level (high/medium/low)
- Notes

## Technologies

- Pure HTML5, CSS3, JavaScript (No frameworks needed)
- LocalStorage for data persistence
- GitHub Pages ready
- Mobile-first responsive design

## Deployment

This dashboard can be deployed on:
- GitHub Pages (free)
- Vercel (free)
- Netlify (free)
- Any static hosting service

## License

MIT License - Feel free to modify and use for your projects
