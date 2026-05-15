# EVA - Engineering Variance Authority

A comprehensive task management and project tracking system built with React, designed for students and professionals managing complex workloads.

## Overview

EVA is an all-in-one web application that helps you manage:

- **Tasks & Workflows** - Track daily tasks with cognitive load monitoring
- **Academic Requirements** - Organize courses and deliverables via the Syllabus Vault
- **Timeline Management** - Visualize project deadlines with the Temporal Loom
- **Incident Tracking** - Log and resolve issues with the Nexus Incident Ledger
- **Resource Inventory** - Manage components and equipment
- **Digital Logic Tools** - Truth table generator and boolean equation solver
- **Focus Sessions** - Pomodoro-style timer with clearance point tracking

## Features

### 1. **Syllabus Vault** (§I)
- Log course codes, deliverables, and deadlines
- Track convergence progress with linked tasks
- Visual progress indicators for each requirement
- Quick task creation directly from course entries

### 2. **Task Matrix** (§II)
- Create and manage tasks with weight-based complexity
- Cognitive load monitoring (max 25 points/day)
- Backlog system for overflow tasks
- Chrono-Monitor: 25-minute focus timer with clearance points
- Epic tagging and course convergence
- Lock matrix during active focus sessions

### 3. **Resource Console** (§VI)
- Physical inventory ledger for components and equipment
- Truth Table Generator: Create and analyze digital logic circuits
- Boolean equation extraction using Quine-McCluskey minimization
- Formula library for storing mathematical and physical equations

### 4. **Temporal Loom** (§IV)
- Visualize deadline branches and task dependencies
- Identify timeline collisions (3+ high-complexity tasks on same date)
- Interactive SVG visualization with animated flows
- Task status indicators (active/completed)

### 5. **Nexus Incident Ledger** (§V)
- Report timeline anomalies and bugs
- Track incident resolution with step-based protocols
- Archive resolved incidents
- Progress tracking with percentage completion

## Technology Stack

- **Frontend**: React 18 + JSX (in-browser transpilation with Babel)
- **Styling**: Tailwind CSS
- **State Management**: React Context API + useReducer
- **Persistence**: Browser localStorage integration
- **Data Visualization**: SVG with CSS animations
- **UI Components**: Custom-designed retro aesthetic

## Getting Started

1. **Open the Application**: Simply open `index.html` in a modern web browser
2. **No Installation Required**: Runs entirely in the browser with CDN resources
3. **Start Organizing**: 
   - Log courses in the Syllabus Vault
   - Create tasks in the Task Matrix
   - Monitor your daily cognitive load
   - Use the Chrono-Monitor for focused work sessions

## Default Sample Data

The application comes with pre-loaded sample data including:
- Example tasks: "Debug Java Thread Sync", "Draft Conic Sections", "Wire 3-bit Adder"
- Sample courses: MTH 301, ENG 202
- Inventory items: Breadboards, ICs, Jumper Wires
- Incident examples for learning the interface

## Architecture

- **Single File Application**: All code embedded in `index.html`
- **State Reducer Pattern**: Central dispatch system for all state changes
- **Context Providers**: MatrixContext for app state, ToastContext for notifications
- **Responsive Design**: Mobile-optimized UI with Tailwind breakpoints
- **Custom Scrollbars**: Styled scrolling throughout interface

## Features Highlights

- ✅ **Persistent Data**: Auto-saves to browser localStorage
- ✅ **No Network Required**: Works completely offline
- ✅ **Accessible**: Keyboard navigation and screen reader support
- ✅ **Mobile Responsive**: Optimized for mobile, tablet, and desktop
- ✅ **Boolean Logic Tools**: Automatic minterm optimization for digital circuits
- ✅ **Retro CRT Aesthetic**: Distinctive vintage computing visual style

## Browser Compatibility

Requires a modern browser with support for:
- ES2020+ JavaScript
- React 18
- CSS Grid and Flexbox
- LocalStorage API

## Use Cases

- 📚 **Students**: Manage courses, assignments, and deadlines
- 🔧 **Engineers**: Track hardware components and circuit designs
- 🎯 **Project Managers**: Monitor timelines and incident resolution
- 🧠 **Productivity**: Focus sessions with clearance point gamification

## License

Open source project - feel free to fork and customize for your needs.

---

**EVA** - Engineering Variance Authority: Taking Control of Chaos, One Task at a Time.
