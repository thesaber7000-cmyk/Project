# Tech Tut: draw.io — A Comprehensive Business Diagramming Tutorial

**BIT 4454: Business Analysis Seminar in IT**

---

## Table of Contents

1. [Part A1: Technology Area Description](#part-a1-technology-area-description)
2. [Part A2: Competitor Comparison](#part-a2-competitor-comparison)
3. [Part B: Step-by-Step Tutorial — Building a Business Process Model for an Order Fulfillment System](#part-b-step-by-step-tutorial)
   - [Chapter 1: Getting Started with draw.io](#chapter-1-getting-started-with-drawio)
   - [Chapter 2: Understanding the draw.io Interface](#chapter-2-understanding-the-drawio-interface)
   - [Chapter 3: Creating an Organization Chart for the Fulfillment Department](#chapter-3-creating-an-organization-chart)
   - [Chapter 4: Building a BPMN Process Diagram for Order Fulfillment](#chapter-4-building-a-bpmn-process-diagram)
   - [Chapter 5: Creating a System Architecture Diagram](#chapter-5-creating-a-system-architecture-diagram)
   - [Chapter 6: Designing a Database Entity-Relationship Diagram](#chapter-6-designing-a-database-er-diagram)
   - [Chapter 7: Building a Customer Journey Map](#chapter-7-building-a-customer-journey-map)
   - [Chapter 8: Creating a Network Infrastructure Diagram](#chapter-8-creating-a-network-infrastructure-diagram)
   - [Chapter 9: Collaboration, Exporting, and Sharing](#chapter-9-collaboration-exporting-and-sharing)
   - [Chapter 10: Advanced Features and Tips for Business Analysts](#chapter-10-advanced-features-and-tips)
4. [Part 4: Best Additional Tutorial Materials](#part-4-best-additional-tutorial-materials)

---

## Part A1: Technology Area Description

### What Is draw.io?

draw.io (now also branded as **diagrams.net**) is a free, open-source, web-based diagramming application used for creating flowcharts, process diagrams, organization charts, UML diagrams, network diagrams, wireframes, and many other types of visual diagrams. It was originally developed by JGraph Ltd and is now maintained by the company behind diagrams.net.

draw.io runs directly in a web browser — no installation is required. It also offers desktop applications for Windows, macOS, and Linux, as well as integrations with cloud storage platforms (Google Drive, OneDrive, Dropbox) and enterprise collaboration tools (Atlassian Confluence, Jira, Microsoft Teams, Google Workspace).

### Why Is draw.io Needed?

In modern business environments, visual communication is essential. Business analysts, project managers, software developers, IT architects, and many other professionals need to create diagrams to:

- **Document business processes**: Flowcharts and BPMN diagrams capture how work gets done, identify bottlenecks, and provide a basis for process improvement.
- **Model system architectures**: IT teams use architecture diagrams to plan, communicate, and document the components of software systems and infrastructure.
- **Design database schemas**: Entity-Relationship (ER) diagrams help database administrators and developers plan and communicate the structure of databases.
- **Map organizational structures**: Org charts help HR departments and managers visualize reporting relationships and team composition.
- **Plan network infrastructure**: Network diagrams show how devices and systems are connected, which is critical for IT operations and security planning.
- **Create wireframes and mockups**: UI/UX designers and product teams use wireframes to prototype user interfaces before development begins.
- **Facilitate stakeholder communication**: Diagrams bridge the gap between technical and non-technical stakeholders by providing a shared visual language.

Without a diagramming tool, teams often resort to ad-hoc solutions (hand-drawn sketches, cluttered spreadsheets, text descriptions) that are difficult to maintain, share, and update. draw.io provides a professional, standardized, and collaborative solution for all of these use cases — at no cost.

### Who Uses draw.io?

draw.io is used by a wide range of professionals and organizations:

- **Business Analysts**: To document current-state ("as-is") and future-state ("to-be") business processes using BPMN notation, create use case diagrams, and map stakeholder interactions.
- **Software Developers and Architects**: To design system architectures, create UML class diagrams, sequence diagrams, and component diagrams.
- **IT Administrators**: To map network topologies, server configurations, and cloud infrastructure layouts.
- **Project Managers**: To create Gantt-chart-style project timelines, work breakdown structures, and decision trees.
- **Product Managers and UX Designers**: To build wireframes, user flow diagrams, and customer journey maps.
- **Educators and Students**: To create visual learning aids, concept maps, and presentation diagrams.
- **Enterprise Teams**: Organizations such as Atlassian (through their Confluence integration), government agencies, universities, and startups use draw.io for team-wide diagramming.

According to the draw.io team, the tool is used by millions of users worldwide, with significant adoption in enterprise environments due to its security model (diagrams are stored on the user's own cloud storage, not on draw.io servers), its open-source nature, and the lack of vendor lock-in.

---

## Part A2: Competitor Comparison

### Major Competitors in the Diagramming Technology Area

The following table compares draw.io with its major competitors across key features relevant to business users:

| Feature / Criterion | **draw.io (diagrams.net)** | **Microsoft Visio** | **Lucidchart** | **Miro** | **Creately** | **Gliffy** |
|---|---|---|---|---|---|---|
| **Pricing** | Free (open-source) | $5–$15/user/month (Microsoft 365 add-on) or one-time purchase ~$310–$580 | Free tier (3 docs); Paid from $7.95/user/month | Free tier (3 boards); Paid from $8/member/month | Free tier (5 docs); Paid from $5/user/month | Free tier (5 diagrams); Paid from $8/user/month |
| **Platform** | Web browser, Desktop (Win/Mac/Linux) | Desktop (Windows only for full version); Web (limited) via Microsoft 365 | Web browser, Desktop (via Electron) | Web browser, Desktop, Mobile (iOS/Android) | Web browser, Desktop | Web browser |
| **Cloud Storage Integration** | Google Drive, OneDrive, Dropbox, GitHub, GitLab, local device | OneDrive, SharePoint | Google Drive, Dropbox, Box, OneDrive | Built-in cloud | Google Drive, OneDrive, Dropbox | Atlassian Cloud only |
| **Collaboration (Real-Time)** | Yes (via cloud storage or Confluence integration) | Yes (via SharePoint/OneDrive online) | Yes (built-in real-time co-editing) | Yes (built-in real-time co-editing, designed for collaboration) | Yes (built-in real-time co-editing) | Limited (Confluence integration) |
| **BPMN Support** | Full BPMN 2.0 shape library | Full BPMN 2.0 support | Full BPMN 2.0 support | Limited (basic flowchart shapes) | Full BPMN 2.0 support | Basic BPMN support |
| **UML Support** | Full UML 2.5 shape library | Full UML support | Full UML support | Limited | Full UML support | Basic UML support |
| **Network Diagram Support** | Cisco, AWS, Azure, GCP shape libraries | Cisco, rack diagrams, basic network | AWS, Azure, GCP shape libraries | Basic shapes only | Basic network shapes | Basic network shapes |
| **Template Library** | 100+ built-in templates | 70+ professional templates | 1000+ templates | 300+ templates | 1000+ templates | 50+ templates |
| **Import/Export Formats** | XML, PNG, JPEG, SVG, PDF, HTML, Visio (.vsdx), CSV import | Native .vsdx, PDF, SVG, PNG, JPEG | Visio import/export, PDF, PNG, JPEG | PDF, PNG, JPEG, CSV | Visio import/export, PDF, PNG, SVG | Visio import/export (limited), PNG, JPEG, SVG |
| **Atlassian Integration** | Confluence, Jira (official plugin) | Limited (via third-party add-ons) | Confluence, Jira (official plugin) | Jira, Confluence (official plugin) | Confluence, Jira | Confluence (official plugin; Gliffy is owned by Atlassian) |
| **Data-Driven Diagrams** | Yes (CSV import to auto-generate diagrams) | Yes (link to external data sources) | Yes (data linking) | No | Limited | No |
| **Offline Support** | Yes (desktop app or local storage) | Yes (desktop app) | Yes (desktop app) | Limited (mobile only) | Yes (desktop app) | No |
| **Open Source** | Yes (Apache 2.0 license) | No (proprietary) | No (proprietary) | No (proprietary) | No (proprietary) | No (proprietary) |
| **Security / Data Privacy** | Diagrams stored on user's own storage; no data stored on draw.io servers | Data stored on Microsoft servers | Data stored on Lucidchart servers | Data stored on Miro servers | Data stored on Creately servers | Data stored on Atlassian servers |
| **API / Automation** | Embed API, URL parameters for automation | VBA/COM automation, Power Automate | REST API, Zapier integration | REST API, Zapier integration | REST API | REST API (via Atlassian) |

### Summary of Competitive Landscape

- **Microsoft Visio** is the long-standing incumbent in enterprise diagramming but carries significant licensing costs and is primarily Windows-only for the full desktop experience.
- **Lucidchart** is the leading cloud-native competitor, offering excellent collaboration and a vast template library, but requires paid plans for serious use.
- **Miro** focuses heavily on collaborative whiteboarding and is less specialized for technical diagramming (BPMN, UML, network diagrams).
- **Creately** and **Gliffy** are solid alternatives but have more limited feature sets compared to draw.io and Lucidchart.
- **draw.io** stands out as the only fully free, open-source option with enterprise-grade features, no vendor lock-in, and strong security properties (data stays on the user's own storage).

---

## Part B: Step-by-Step Tutorial

### Novel Business Application: Order Fulfillment System for "Summit Outdoor Gear Co."

> **Note**: This tutorial uses a fictional company, "Summit Outdoor Gear Co.," as a novel example case. Summit Outdoor Gear is a mid-size e-commerce retailer specializing in outdoor and camping equipment. The company is expanding its operations and needs to document and improve its order fulfillment process. As a business analyst, you have been asked to create a comprehensive set of diagrams to model the current process, propose improvements, and communicate the system architecture to stakeholders.
>
> This example is directly applicable to team projects involving e-commerce, supply chain management, or operations improvement.

---

### Chapter 1: Getting Started with draw.io

#### 1.1 Accessing draw.io

There are two main ways to access draw.io:

**Option A: Web Browser (Recommended for Quick Start)**

1. Open your web browser (Chrome, Firefox, Edge, or Safari are all supported).
2. Navigate to **https://app.diagrams.net** (or **https://draw.io**, which redirects to the same site).
3. You will be greeted with a dialog asking where you would like to save your diagrams.

> *[Screenshot: Browser showing the draw.io landing page with the storage selection dialog. Options displayed include Google Drive, OneDrive, Device, GitHub, GitLab, Dropbox, and "Decide later."]*

**Option B: Desktop Application**

1. Navigate to **https://github.com/jgraph/drawio-desktop/releases** in your web browser.
2. Download the installer for your operating system:
   - **Windows**: Download the `.exe` installer (e.g., `draw.io-21.x.x-windows-installer.exe`).
   - **macOS**: Download the `.dmg` file.
   - **Linux**: Download the `.AppImage`, `.deb`, or `.rpm` file depending on your distribution.
3. Run the installer and follow the on-screen prompts to install the application.
4. Launch draw.io from your Applications menu or desktop shortcut.

> *[Screenshot: The draw.io desktop application installer download page on GitHub, highlighting the Windows .exe file.]*

> *[Screenshot: The draw.io desktop application after installation, showing the welcome screen.]*

#### 1.2 Choosing a Storage Location

When you first open draw.io (web version), you must choose where your diagram files will be saved:

1. **Google Drive**: Best if your team uses Google Workspace. Enables real-time collaboration.
2. **OneDrive**: Best if your team uses Microsoft 365. Enables sharing via SharePoint.
3. **Device (Local Storage)**: Best for offline work or when you do not want to use cloud storage. Files are saved to your computer's hard drive.
4. **GitHub / GitLab**: Best for software development teams who want to version-control their diagrams alongside code.
5. **Dropbox**: Another cloud storage option.

For this tutorial, we will select **Device** to keep things simple and avoid requiring any cloud account setup.

1. Click **"Device"** in the storage selection dialog.
2. draw.io will open with a blank canvas, ready for you to start creating diagrams.

> *[Screenshot: The storage selection dialog with "Device" highlighted and the cursor clicking on it.]*

#### 1.3 Creating Your First Diagram File

1. After selecting Device storage, draw.io presents a dialog to create a new diagram or open an existing one.
2. Click **"Create New Diagram"**.
3. In the "Create New Diagram" dialog:
   - **Filename**: Enter `Summit_OrgChart.drawio`
   - **Template**: Select "Blank Diagram" (we will build from scratch).
4. Click **"Create"**.

> *[Screenshot: The "Create New Diagram" dialog with the filename "Summit_OrgChart.drawio" entered and "Blank Diagram" selected.]*

You now have a blank canvas ready for diagramming.

> *[Screenshot: The draw.io interface showing a completely blank canvas with the default toolbars and panels visible.]*

---

### Chapter 2: Understanding the draw.io Interface

Before we start creating business diagrams, let's familiarize ourselves with the draw.io interface components.

#### 2.1 The Main Interface Layout

The draw.io interface consists of the following key areas:

> *[Screenshot: The full draw.io interface with numbered annotations pointing to each area described below.]*

1. **Menu Bar** (top): Contains File, Edit, View, Format, Extras, and Help menus. Use this for file operations, undo/redo, and accessing settings.

2. **Toolbar** (below menu bar): Contains quick-access buttons for common actions:
   - Undo / Redo
   - Delete
   - Move to Front / Move to Back (layer ordering)
   - Fill Color / Font Color / Line Color
   - Shadow toggle
   - Connection point toggle
   - Zoom controls

3. **Shape Panel** (left side): Contains the shape libraries organized into categories:
   - **General**: Basic shapes (rectangles, circles, arrows, etc.)
   - **UML**: UML class, sequence, activity, and state diagram shapes
   - **BPMN**: Business Process Model and Notation shapes
   - **Flowchart**: Standard flowchart symbols
   - **Network**: Cisco, AWS, Azure, and GCP shapes
   - **Other Libraries**: Can be enabled via "More Shapes" at the bottom

4. **Canvas** (center): The main drawing area where you place and connect shapes.

5. **Format Panel** (right side): Shows properties of the currently selected element:
   - **Style**: Fill color, stroke color, opacity, shadow
   - **Text**: Font, size, alignment, text color
   - **Arrange**: Position (x, y), size (width, height), rotation, layer

6. **Status Bar** (bottom): Shows zoom level, page information, and other status indicators.

#### 2.2 Navigating the Canvas

- **Zoom In/Out**: Use `Ctrl + Mouse Scroll` or the zoom controls in the toolbar.
- **Pan**: Hold `Shift + Mouse Scroll` to scroll horizontally, or hold the middle mouse button and drag.
- **Fit to Page**: Press `Ctrl + Shift + H` to fit the entire diagram in the visible area.
- **Select All**: Press `Ctrl + A` to select all shapes on the canvas.

#### 2.3 Enabling Additional Shape Libraries

For our business diagrams, we need some specialized shape libraries:

1. Click **"+ More Shapes"** at the bottom of the Shape Panel on the left.
2. In the "Shapes" dialog that appears, you will see categories of shape libraries.
3. Enable the following libraries by clicking the toggle switches next to each:
   - Under **Software**: Enable **UML** (if not already enabled).
   - Under **Other**: Enable **BPMN** shapes.
   - Under **Networking**: Enable **AWS**, **Azure**, and **Cisco** shapes (we'll use some of these for our system architecture diagram).
4. Click **"Apply"** to close the dialog.

> *[Screenshot: The "More Shapes" dialog showing the various shape library categories with BPMN, UML, and Networking libraries being toggled on.]*

The newly enabled shape libraries will now appear in the Shape Panel on the left side of the interface.

#### 2.4 Understanding Connectors

Connectors (also called edges or lines) are used to show relationships between shapes. draw.io supports several types of connectors:

- **Straight Line**: A direct line between two shapes.
- **Orthogonal (Right-Angle)**: A line that uses only horizontal and vertical segments with right-angle turns. This is the most common style for flowcharts and process diagrams.
- **Curved**: A smooth curved line between shapes.
- **Entity Relation**: A specialized connector for ER diagrams with crow's foot notation.

To create a connector:
1. Hover over a shape until you see blue arrow icons appear on its edges.
2. Click and drag from one of these blue arrows to another shape.
3. Release the mouse button when hovering over the target shape.

> *[Screenshot: A shape on the canvas with blue connector arrows visible on all four sides, and the cursor dragging a connector line toward another shape.]*

To change the connector style:
1. Select the connector by clicking on it.
2. In the Format Panel on the right, look for the **Style** section.
3. Click the **"Connection"** dropdown and choose the desired line style.

---

### Chapter 3: Creating an Organization Chart for the Fulfillment Department

Our first business diagram will be an organization chart showing the structure of Summit Outdoor Gear Co.'s order fulfillment department.

#### 3.1 Planning the Org Chart

Summit Outdoor Gear Co.'s order fulfillment department has the following structure:

- **VP of Operations**: Sarah Mitchell
  - **Director of Warehousing**: James Chen
    - **Warehouse Manager – East**: Maria Lopez
      - 3 Warehouse Associates
    - **Warehouse Manager – West**: David Kim
      - 3 Warehouse Associates
  - **Director of Shipping & Logistics**: Priya Patel
    - **Shipping Manager**: Tom Harris
      - 2 Shipping Coordinators
    - **Logistics Analyst**: Emily Zhang
  - **Director of Customer Service**: Robert Johnson
    - **CS Team Lead**: Angela Davis
      - 4 Customer Service Representatives

#### 3.2 Creating the Top-Level Box

1. Open the file `Summit_OrgChart.drawio` (or create a new diagram with this name).
2. In the Shape Panel on the left, find the **General** category.
3. Locate the **Rectangle** shape.
4. Drag the rectangle onto the canvas and drop it near the top center of the canvas.
5. Double-click the rectangle to edit its text.
6. Type: **Sarah Mitchell** and press `Enter`, then type **VP of Operations**.
7. Click outside the shape to deselect it.

> *[Screenshot: A single rectangle on the canvas containing "Sarah Mitchell" on the first line and "VP of Operations" on the second line.]*

#### 3.3 Styling the Top-Level Box

1. Click on the rectangle to select it.
2. In the Format Panel on the right:
   - Set **Fill Color** to a dark blue (`#1A3C6E`).
   - Set **Font Color** to white (`#FFFFFF`).
   - Set **Font Size** to `14`.
   - Set **Font Style** to **Bold**.
   - Set **Width** to `200` and **Height** to `60`.
3. Optionally, add rounded corners:
   - Right-click the shape → **Edit Style**.
   - In the style editor, add `rounded=1;` to the style string.
   - Click **OK**.

> *[Screenshot: The styled rectangle with a dark blue background, white bold text, and rounded corners, showing "Sarah Mitchell / VP of Operations."]*

#### 3.4 Adding the Director-Level Boxes

1. Select the "Sarah Mitchell" box.
2. Press `Ctrl + D` to duplicate the shape. A copy will appear slightly offset from the original.
3. Drag the copy down and to the left to position it below and to the left of the original.
4. Double-click the copy and change the text to **James Chen** / **Director of Warehousing**.
5. Change the fill color to a medium blue (`#2E5FA1`) to visually distinguish the director level.
6. Repeat steps 2–5 to create two more director-level boxes:
   - **Priya Patel** / **Director of Shipping & Logistics** (positioned below center)
   - **Robert Johnson** / **Director of Customer Service** (positioned below right)

> *[Screenshot: Four boxes on the canvas — one dark blue VP box at the top and three medium blue director boxes arranged in a row below it.]*

#### 3.5 Connecting the VP to Directors

1. Hover over the bottom edge of the "Sarah Mitchell" box until the blue connector arrow appears.
2. Click and drag from the blue arrow down to the "James Chen" box.
3. Release when the target box is highlighted (turns blue).
4. The connector should snap into place automatically.
5. Repeat for the other two director boxes ("Priya Patel" and "Robert Johnson").

> *[Screenshot: The VP box connected to all three director boxes with orthogonal connector lines.]*

#### 3.6 Adding Manager and Staff Levels

Continue the same process of duplicating and connecting shapes for each subsequent level:

**Under James Chen (Director of Warehousing):**
1. Create two manager boxes with a lighter blue fill (`#5B8ACF`):
   - **Maria Lopez** / **Warehouse Manager – East**
   - **David Kim** / **Warehouse Manager – West**
2. Connect James Chen to both managers.
3. Under each warehouse manager, create grouped boxes representing:
   - **3 Warehouse Associates** (under Maria Lopez)
   - **3 Warehouse Associates** (under David Kim)
4. Use a light blue fill (`#B3CCE6`) for the associate level.

**Under Priya Patel (Director of Shipping & Logistics):**
1. Create two boxes:
   - **Tom Harris** / **Shipping Manager** (lighter blue `#5B8ACF`)
   - **Emily Zhang** / **Logistics Analyst** (lighter blue `#5B8ACF`)
2. Connect Priya Patel to both.
3. Under Tom Harris, create:
   - **2 Shipping Coordinators** (light blue `#B3CCE6`)

**Under Robert Johnson (Director of Customer Service):**
1. Create one box:
   - **Angela Davis** / **CS Team Lead** (lighter blue `#5B8ACF`)
2. Connect Robert Johnson to Angela Davis.
3. Under Angela Davis, create:
   - **4 Customer Service Representatives** (light blue `#B3CCE6`)

> *[Screenshot: The complete organization chart with all levels filled in, showing the VP at the top, three directors in the second row, managers in the third row, and staff in the fourth row. The color gradient from dark to light blue indicates the hierarchy.]*

#### 3.7 Auto-Layout for Organization Charts

draw.io provides an automatic layout feature that can arrange your org chart neatly:

1. Select all shapes on the canvas (`Ctrl + A`).
2. Go to **Format** → **Layout** → **Tree** → **Vertical Tree**.
3. draw.io will automatically rearrange the shapes into a clean hierarchical tree layout.
4. You may need to adjust spacing manually after the auto-layout by dragging shapes.

> *[Screenshot: The organization chart after applying the Vertical Tree auto-layout, showing clean, evenly spaced arrangement of all boxes and connectors.]*

#### 3.8 Saving the Diagram

1. Go to **File** → **Save** (or press `Ctrl + S`).
2. If using Device storage, your browser will download the file `Summit_OrgChart.drawio`.
3. Save it to a folder on your computer where you can easily find it later.

> *[Screenshot: The File menu open with "Save" highlighted.]*

---

### Chapter 4: Building a BPMN Process Diagram for Order Fulfillment

Now we will create a Business Process Model and Notation (BPMN) diagram showing how Summit Outdoor Gear Co. fulfills customer orders from receipt to delivery.

#### 4.1 Creating a New Diagram

1. Go to **File** → **New** (or press `Ctrl + N`).
2. Enter the filename: `Summit_OrderFulfillment_BPMN.drawio`
3. Select **Blank Diagram** as the template.
4. Click **Create**.

#### 4.2 Adding BPMN Swim Lanes (Pools)

BPMN uses "swim lanes" (also called pools) to show which department or role is responsible for each activity.

1. In the Shape Panel on the left, scroll down to the **BPMN** section (or search for "pool" in the search box at the top of the Shape Panel).
2. Drag a **Pool** shape onto the canvas.
3. Resize the pool to be approximately 1200 pixels wide and 200 pixels tall.
4. Double-click the pool's label area (on the left side) and type: **Customer**.

> *[Screenshot: A single BPMN pool on the canvas labeled "Customer."]*

5. Repeat to create additional pools below the first one, for:
   - **E-Commerce Platform** (system lane)
   - **Warehouse Team**
   - **Shipping & Logistics**
   - **Customer Service**

6. Arrange the pools vertically, stacked on top of each other with small gaps between them.

> *[Screenshot: Five BPMN pools stacked vertically and labeled: Customer, E-Commerce Platform, Warehouse Team, Shipping & Logistics, Customer Service.]*

#### 4.3 Adding the Start Event

1. In the BPMN shapes library, find the **Start Event** (a thin-bordered circle).
2. Drag it into the **Customer** swim lane on the left side.
3. Label it: **Customer Places Order**.

> *[Screenshot: A BPMN start event (green circle) placed in the Customer lane, labeled "Customer Places Order."]*

#### 4.4 Adding Activities (Tasks)

BPMN activities are shown as rounded rectangles. Add the following activities in order:

**In the Customer Lane:**
1. Drag a **Task** shape (rounded rectangle) to the right of the start event.
2. Label it: **Browse Products & Add to Cart**.
3. Drag another task to the right: **Enter Payment & Shipping Info**.
4. Drag another task to the right: **Submit Order**.

**In the E-Commerce Platform Lane:**
5. Drag a task: **Validate Payment**.
6. Drag a task: **Generate Order Confirmation**.
7. Drag a task: **Send Order to Warehouse**.

**In the Warehouse Team Lane:**
8. Drag a task: **Receive Order Notification**.
9. Drag a task: **Pick Items from Shelves**.
10. Drag a task: **Pack Order**.
11. Drag a task: **Print Shipping Label**.
12. Drag a task: **Hand Off to Shipping**.

**In the Shipping & Logistics Lane:**
13. Drag a task: **Receive Packed Order**.
14. Drag a task: **Select Carrier & Calculate Route**.
15. Drag a task: **Dispatch Order**.
16. Drag a task: **Track Shipment**.

**In the Customer Service Lane:**
17. Drag a task: **Send Tracking Info to Customer**.
18. Drag a task: **Handle Delivery Issues** (if any).

> *[Screenshot: All BPMN task boxes placed within their respective swim lanes, arranged left to right.]*

#### 4.5 Adding Gateways (Decision Points)

BPMN gateways are diamond shapes that represent decision points or parallel paths:

1. After **Validate Payment** in the E-Commerce Platform lane, add an **Exclusive Gateway** (diamond with an "X").
2. Label it: **Payment Valid?**
3. From the gateway, draw two paths:
   - **Yes**: Continues to **Generate Order Confirmation**.
   - **No**: Connects to a new task **Notify Customer of Payment Failure** → **End Event** (labeled "Order Cancelled").

4. After **Track Shipment** in the Shipping & Logistics lane, add another Exclusive Gateway.
5. Label it: **Delivery Successful?**
6. From the gateway:
   - **Yes**: Connects to an **End Event** in the Customer lane labeled **Order Delivered**.
   - **No**: Connects to **Handle Delivery Issues** in the Customer Service lane.

> *[Screenshot: The BPMN diagram with exclusive gateways added, showing the decision diamonds and branching paths with "Yes" and "No" labels on the connector lines.]*

#### 4.6 Connecting All Activities with Sequence Flows

1. Connect all activities in order using sequence flow arrows (solid arrows with filled arrowheads):
   - Start Event → Browse Products → Enter Payment Info → Submit Order
   - Submit Order → (message flow to) Validate Payment
   - Validate Payment → Payment Valid? Gateway
   - Gateway (Yes) → Generate Order Confirmation → Send Order to Warehouse
   - Send Order to Warehouse → (message flow to) Receive Order Notification
   - Receive Order Notification → Pick Items → Pack Order → Print Shipping Label → Hand Off to Shipping
   - Hand Off to Shipping → (message flow to) Receive Packed Order
   - Receive Packed Order → Select Carrier → Dispatch Order → Track Shipment
   - Track Shipment → Delivery Successful? Gateway
   - Gateway (Yes) → End Event
   - Gateway (No) → Handle Delivery Issues
   - Generate Order Confirmation → (message flow to) Send Tracking Info to Customer

2. For flows that cross swim lanes (message flows), use **dashed lines with open arrowheads** (BPMN message flow notation):
   - Right-click the connector → **Edit Style**
   - Change the style to include `dashed=1;endArrow=open;`

> *[Screenshot: The complete BPMN diagram with all sequence flows (solid arrows) and message flows (dashed arrows) connecting all activities across all five swim lanes.]*

#### 4.7 Adding Annotations and Data Objects

1. Add a **Data Object** (page icon with folded corner) near the "Generate Order Confirmation" task.
   - Label it: **Order Confirmation Email**.
   - Connect it with a **Data Association** (dashed line, no arrowhead) to the task.

2. Add a **Text Annotation** (bracket with text) near the "Pick Items from Shelves" task.
   - Text: **"Average pick time: 15 min per order. Target: 12 min."**

3. Add a **Data Store** (cylinder shape) near the "Validate Payment" task.
   - Label it: **Customer Database**.
   - Connect with a data association.

> *[Screenshot: The BPMN diagram with data objects (email icon), text annotations (bracket notes), and a data store (cylinder) added to provide additional context.]*

#### 4.8 Final BPMN Styling

1. Select all start events and set their fill color to green (`#00CC66`).
2. Select all end events and set their fill color to red (`#CC3333`).
3. Select all gateways and set their fill color to yellow (`#FFCC00`).
4. Select all tasks and set their fill color to light blue (`#DAE8FC`), with dark blue borders (`#6C8EBF`).
5. Adjust the swim lane header colors to match our org chart color scheme.

> *[Screenshot: The final, fully styled BPMN process diagram for the order fulfillment process, with color-coded events, gateways, and tasks across five swim lanes.]*

#### 4.9 Saving the BPMN Diagram

1. Press `Ctrl + S` to save the diagram.
2. The file `Summit_OrderFulfillment_BPMN.drawio` is saved to your chosen storage location.

---

### Chapter 5: Creating a System Architecture Diagram

Next, we will create a system architecture diagram showing the technology components that support Summit Outdoor Gear Co.'s order fulfillment process.

#### 5.1 Creating a New Diagram

1. **File** → **New** → Filename: `Summit_SystemArchitecture.drawio` → **Blank Diagram** → **Create**.

#### 5.2 Designing the Architecture Layers

We will organize the architecture into three horizontal layers:

- **Presentation Layer** (top): Customer-facing web and mobile interfaces
- **Application Layer** (middle): Backend services and APIs
- **Data Layer** (bottom): Databases and storage

1. Create three large rectangles spanning the width of the canvas:
   - Top rectangle: Label **"Presentation Layer"**, fill color `#E1F5FE` (light blue)
   - Middle rectangle: Label **"Application Layer"**, fill color `#FFF3E0` (light orange)
   - Bottom rectangle: Label **"Data Layer"**, fill color `#E8F5E9` (light green)
2. Set each rectangle's opacity to 50% so that shapes placed inside them are clearly visible.

> *[Screenshot: Three colored layer rectangles stacked vertically, labeled "Presentation Layer," "Application Layer," and "Data Layer."]*

#### 5.3 Adding Presentation Layer Components

Inside the **Presentation Layer**, add the following shapes:

1. **Customer Web Portal** (use a browser/monitor icon shape):
   - Drag a "Web Browser" shape from the Mockup shapes or use a standard rectangle with a monitor icon.
   - Label: **Customer Web Portal (React.js)**
   - Position: Left side of the presentation layer.

2. **Mobile App** (use a mobile phone icon shape):
   - Label: **Mobile App (React Native)**
   - Position: Center of the presentation layer.

3. **Admin Dashboard** (use a browser/monitor icon shape):
   - Label: **Admin Dashboard (React.js)**
   - Position: Right side of the presentation layer.

> *[Screenshot: Three icons in the Presentation Layer — a web browser, a mobile phone, and another web browser, labeled with their respective names and technologies.]*

#### 5.4 Adding Application Layer Components

Inside the **Application Layer**, add:

1. **API Gateway**: Rectangle labeled **API Gateway (AWS API Gateway)**.
2. **Order Service**: Rectangle labeled **Order Management Service (Node.js)**.
3. **Inventory Service**: Rectangle labeled **Inventory Service (Python/Flask)**.
4. **Payment Service**: Rectangle labeled **Payment Processing Service (Stripe API)**.
5. **Notification Service**: Rectangle labeled **Notification Service (AWS SNS/SES)**.
6. **Shipping Service**: Rectangle labeled **Shipping & Tracking Service (ShipStation API)**.
7. **Authentication Service**: Rectangle labeled **Auth Service (AWS Cognito)**.

Arrange these components in a logical flow from left to right.

> *[Screenshot: Seven service rectangles arranged inside the Application Layer, each labeled with the service name and technology stack.]*

#### 5.5 Adding Data Layer Components

Inside the **Data Layer**, add:

1. **Order Database**: Cylinder shape (database) labeled **Order DB (PostgreSQL on AWS RDS)**.
2. **Inventory Database**: Cylinder shape labeled **Inventory DB (PostgreSQL on AWS RDS)**.
3. **Customer Database**: Cylinder shape labeled **Customer DB (PostgreSQL on AWS RDS)**.
4. **File Storage**: Cloud shape labeled **File Storage (AWS S3)** — for storing product images, invoices, shipping labels.
5. **Cache**: Rectangle labeled **Cache Layer (Redis on AWS ElastiCache)**.

> *[Screenshot: Database cylinders and storage shapes arranged in the Data Layer, labeled with their names and technologies.]*

#### 5.6 Connecting the Components

Draw connectors between the layers to show data flow:

1. **Presentation → API Gateway**: All three front-end components connect to the API Gateway via REST/HTTPS arrows.
2. **API Gateway → Services**: The API Gateway connects to each microservice.
3. **Services → Databases**: Each service connects to its respective database(s).
4. **Services → External APIs**: Payment Service connects to an external shape labeled **Stripe** (outside the layers). Shipping Service connects to **ShipStation** (external).

Label each connector with the communication protocol (e.g., "HTTPS", "REST API", "SQL", "gRPC").

> *[Screenshot: The complete system architecture diagram with all three layers, all components, and all connections labeled with protocols.]*

#### 5.7 Adding a Legend

1. In a corner of the diagram, create a small legend box:
   - Blue shapes = Presentation components
   - Orange shapes = Application services
   - Green shapes = Data stores
   - Dashed borders = External services (third-party)

> *[Screenshot: The architecture diagram with a color-coded legend box in the bottom-right corner.]*

#### 5.8 Saving

Press `Ctrl + S` to save `Summit_SystemArchitecture.drawio`.

---

### Chapter 6: Designing a Database Entity-Relationship Diagram

#### 6.1 Creating a New Diagram

1. **File** → **New** → Filename: `Summit_ERDiagram.drawio` → Select template: **Entity Relation** (from the template gallery) or **Blank Diagram** → **Create**.

#### 6.2 Adding Entities

For our order fulfillment system, we need the following entities (tables):

1. **Customer**
   - CustomerID (PK)
   - FirstName
   - LastName
   - Email
   - Phone
   - ShippingAddress
   - BillingAddress
   - AccountCreatedDate

2. **Product**
   - ProductID (PK)
   - ProductName
   - Description
   - Category
   - Price
   - Weight
   - SKU

3. **Order**
   - OrderID (PK)
   - CustomerID (FK)
   - OrderDate
   - OrderStatus
   - TotalAmount
   - ShippingMethod
   - TrackingNumber

4. **OrderItem**
   - OrderItemID (PK)
   - OrderID (FK)
   - ProductID (FK)
   - Quantity
   - UnitPrice
   - Subtotal

5. **Inventory**
   - InventoryID (PK)
   - ProductID (FK)
   - WarehouseID (FK)
   - QuantityOnHand
   - ReorderLevel
   - LastRestockedDate

6. **Warehouse**
   - WarehouseID (PK)
   - WarehouseName
   - Location
   - Capacity

7. **Shipment**
   - ShipmentID (PK)
   - OrderID (FK)
   - CarrierName
   - TrackingNumber
   - ShipDate
   - EstimatedDeliveryDate
   - ActualDeliveryDate
   - ShipmentStatus

8. **Payment**
   - PaymentID (PK)
   - OrderID (FK)
   - PaymentMethod
   - PaymentDate
   - Amount
   - TransactionStatus
   - TransactionID

To create each entity in draw.io:

1. In the Shape Panel, search for **"Entity"** or go to the **UML** section and find the **Class** shape.
2. Alternatively, use the **Entity Relation** shapes (available under **More Shapes → Software → Entity Relation**).
3. Drag an entity shape onto the canvas.
4. Double-click the header to set the entity name (e.g., **Customer**).
5. Click inside the attributes area and type each attribute, one per line.
6. Mark primary keys with **PK** and foreign keys with **FK**.

> *[Screenshot: A single entity shape for the "Customer" table, showing the entity name in the header and all eight attributes listed below with PK marked next to CustomerID.]*

Repeat for all eight entities, arranging them on the canvas with related entities positioned near each other.

> *[Screenshot: All eight entity shapes arranged on the canvas in a logical layout, with Customer and Order near the top, OrderItem and Product in the middle, and Warehouse, Inventory, Shipment, and Payment around the edges.]*

#### 6.3 Adding Relationships

Draw connectors between entities to show their relationships, using crow's foot notation:

1. **Customer → Order**: One-to-Many (one customer can have many orders)
   - Draw a connector from Customer to Order.
   - Right-click the connector → **Edit Style**.
   - Set the source end to `endArrow=ERone` and the target end to `startArrow=ERmany`.

2. **Order → OrderItem**: One-to-Many (one order can have many line items)

3. **Product → OrderItem**: One-to-Many (one product can appear in many order items)

4. **Product → Inventory**: One-to-Many (one product can be in multiple warehouse locations)

5. **Warehouse → Inventory**: One-to-Many (one warehouse holds inventory for many products)

6. **Order → Shipment**: One-to-One (each order has one shipment)

7. **Order → Payment**: One-to-One (each order has one payment transaction)

For each relationship:
1. Select the connector.
2. In the Style panel, set the appropriate crow's foot endings:
   - **One** side: Use `ERone` (single line)
   - **Many** side: Use `ERmany` (crow's foot with three tines)
   - **Zero or One**: Use `ERzeroToOne`
   - **One or Many**: Use `ERoneToMany`
3. Label the connector with the relationship description (e.g., "places", "contains", "stored in").

> *[Screenshot: The ER diagram with crow's foot connectors between all entities, labeled with relationship descriptions such as "places," "contains," "stored in," and "tracks."]*

#### 6.4 Styling the ER Diagram

1. Color-code entities by domain:
   - **Customer-related** (Customer): Blue (`#DAE8FC`)
   - **Order-related** (Order, OrderItem, Payment): Orange (`#FFE6CC`)
   - **Product-related** (Product, Inventory): Green (`#D5E8D4`)
   - **Logistics-related** (Warehouse, Shipment): Purple (`#E1D5E7`)
2. Bold the primary key attributes in each entity.
3. Italicize foreign key attributes.

> *[Screenshot: The color-coded ER diagram with entities grouped by domain color, showing all relationships with crow's foot notation.]*

#### 6.5 Saving

Press `Ctrl + S` to save `Summit_ERDiagram.drawio`.

---

### Chapter 7: Building a Customer Journey Map

#### 7.1 Creating a New Diagram

1. **File** → **New** → Filename: `Summit_CustomerJourneyMap.drawio` → **Blank Diagram** → **Create**.

#### 7.2 Setting Up the Journey Map Structure

A customer journey map tracks the customer's experience across different stages of interaction with the business.

1. Create a horizontal header row across the top with the following journey stages (use colored rectangles):
   - **Awareness** (light yellow `#FFF9C4`)
   - **Consideration** (light orange `#FFE0B2`)
   - **Purchase** (light green `#C8E6C9`)
   - **Fulfillment** (light blue `#BBDEFB`)
   - **Post-Purchase** (light purple `#E1BEE7`)

2. Below the header row, create horizontal swim lanes for:
   - **Customer Actions**: What the customer does at each stage
   - **Touchpoints**: The channels/platforms the customer interacts with
   - **Customer Emotions**: The customer's emotional state (happy, neutral, frustrated)
   - **Pain Points**: Problems or frustrations the customer experiences
   - **Opportunities**: Business improvement opportunities

> *[Screenshot: The customer journey map framework with five stage columns and five rows, creating a grid structure.]*

#### 7.3 Filling In the Journey Map

**Awareness Stage:**
- Customer Actions: "Sees social media ad" → "Searches Google for outdoor gear"
- Touchpoints: Instagram, Google Search, Company Blog
- Emotions: Curious 😊
- Pain Points: "Hard to find specific gear categories"
- Opportunities: "Improve SEO for niche product categories"

**Consideration Stage:**
- Customer Actions: "Compares products on website" → "Reads reviews" → "Checks competitor prices"
- Touchpoints: Company Website, Review Sites, Price Comparison Tools
- Emotions: Interested but uncertain 😐
- Pain Points: "Product comparison is difficult on mobile"
- Opportunities: "Add side-by-side product comparison feature"

**Purchase Stage:**
- Customer Actions: "Adds items to cart" → "Enters payment info" → "Completes checkout"
- Touchpoints: Shopping Cart, Payment Gateway, Order Confirmation Email
- Emotions: Excited about purchase 😊
- Pain Points: "Checkout has too many steps (5 pages)"
- Opportunities: "Streamline checkout to 2-3 steps"

**Fulfillment Stage:**
- Customer Actions: "Tracks order" → "Waits for delivery" → "Receives package"
- Touchpoints: Tracking Portal, Email Notifications, Delivery Driver
- Emotions: Anxious during waiting 😟 → Happy at delivery 😊
- Pain Points: "Tracking updates are infrequent"
- Opportunities: "Implement real-time GPS tracking"

**Post-Purchase Stage:**
- Customer Actions: "Inspects product" → "Writes review" → "Contacts support" (if issue)
- Touchpoints: Product, Review Platform, Customer Support Chat
- Emotions: Satisfied 😊 or Frustrated 😡 (if defective)
- Pain Points: "Return process is complicated"
- Opportunities: "Simplify returns with prepaid shipping labels"

For each cell, use:
- **Rounded rectangles** for actions and touchpoints
- **Emoji or icon shapes** for emotions
- **Red-bordered shapes** for pain points
- **Green-bordered shapes** for opportunities

> *[Screenshot: The completed customer journey map with all five stages filled in, showing customer actions, touchpoints, emotions (using emoji icons), pain points (red), and opportunities (green) across the entire customer journey.]*

#### 7.4 Adding an Emotion Curve

1. Use the **freehand draw** tool or create a **curved line** that passes through the emotion row.
2. The line should go up (positive emotions) during Awareness and Purchase, dip down during Fulfillment (waiting anxiety), and recover in Post-Purchase.
3. Set the line color to a bright color like orange (`#FF6600`) and increase the stroke width to 3px.

> *[Screenshot: The customer journey map with an orange emotion curve overlaid on the Emotions row, showing the ups and downs of the customer's emotional experience.]*

#### 7.5 Saving

Press `Ctrl + S` to save `Summit_CustomerJourneyMap.drawio`.

---

### Chapter 8: Creating a Network Infrastructure Diagram

#### 8.1 Creating a New Diagram

1. **File** → **New** → Filename: `Summit_NetworkDiagram.drawio` → **Blank Diagram** → **Create**.

#### 8.2 Enabling Network Shape Libraries

1. Click **"+ More Shapes"** at the bottom of the Shape Panel.
2. Under **Networking**, enable:
   - **AWS 19** (or the latest AWS shape library)
   - **Cisco** shapes
   - **General networking** shapes
3. Click **Apply**.

#### 8.3 Designing the Network Topology

We will design the AWS cloud infrastructure for Summit Outdoor Gear Co.'s e-commerce platform:

**Internet / External Zone:**
1. Drag a **Cloud** shape to the top of the canvas.
2. Label it: **Internet**.
3. Below the cloud, add:
   - **AWS CloudFront** (CDN icon): Label **CloudFront CDN**
   - **AWS Route 53** (DNS icon): Label **Route 53 DNS**

**VPC (Virtual Private Cloud):**
4. Create a large rectangle labeled **VPC (10.0.0.0/16)** with a dashed border.
5. Inside the VPC, create two subnet regions:
   - **Public Subnet** (10.0.1.0/24): Light green background
   - **Private Subnet** (10.0.2.0/24): Light blue background

**Public Subnet Components:**
6. Add the following in the Public Subnet:
   - **Application Load Balancer**: AWS ALB icon, label **ALB**
   - **NAT Gateway**: AWS NAT Gateway icon
   - **Bastion Host**: EC2 icon, label **Bastion Host (SSH Jump Box)**

**Private Subnet Components:**
7. Add the following in the Private Subnet:
   - **EC2 Auto Scaling Group**: Multiple EC2 icons grouped together, label **Web Servers (Auto Scaling Group)**
   - **RDS Instance**: AWS RDS icon, label **PostgreSQL RDS (Primary)**
   - **RDS Read Replica**: Another AWS RDS icon, label **PostgreSQL RDS (Read Replica)**
   - **ElastiCache**: AWS ElastiCache icon, label **Redis Cache**
   - **S3 Bucket**: AWS S3 icon, label **Product Images & Documents (S3)**

**External Services:**
8. Outside the VPC, add:
   - **Stripe** (generic cloud/API icon): label **Stripe Payment API**
   - **ShipStation** (generic cloud/API icon): label **ShipStation Shipping API**
   - **AWS SES** (email icon): label **SES Email Service**

> *[Screenshot: The complete network infrastructure diagram showing the Internet cloud at the top, CloudFront and Route 53, the VPC with public and private subnets containing all AWS services, and external API integrations.]*

#### 8.4 Connecting Network Components

Draw connectors to show network traffic flow:

1. Internet → CloudFront → ALB → EC2 Web Servers (HTTPS)
2. EC2 Web Servers → RDS (SQL over TCP 5432)
3. EC2 Web Servers → ElastiCache (Redis over TCP 6379)
4. EC2 Web Servers → S3 (HTTPS)
5. EC2 Web Servers → External APIs (HTTPS via NAT Gateway)
6. Bastion Host → EC2 Web Servers (SSH over TCP 22)
7. RDS Primary → RDS Read Replica (async replication)

Label each connection with the protocol and port number.

> *[Screenshot: The network diagram with all connections drawn and labeled with protocols and port numbers.]*

#### 8.5 Adding Security Groups

Add dashed-bordered rectangles around groups of resources to represent AWS Security Groups:

1. **SG-Web**: Around the ALB and EC2 instances — allows inbound HTTP/HTTPS (80/443)
2. **SG-DB**: Around the RDS instances — allows inbound PostgreSQL (5432) from SG-Web only
3. **SG-Cache**: Around ElastiCache — allows inbound Redis (6379) from SG-Web only
4. **SG-Bastion**: Around the Bastion Host — allows inbound SSH (22) from specific IP ranges only

> *[Screenshot: The network diagram with security group boundaries drawn as dashed rectangles, each labeled with the security group name and its inbound/outbound rules.]*

#### 8.6 Saving

Press `Ctrl + S` to save `Summit_NetworkDiagram.drawio`.

---

### Chapter 9: Collaboration, Exporting, and Sharing

#### 9.1 Exporting Diagrams

draw.io supports multiple export formats for sharing your diagrams:

**Exporting as PNG Image:**
1. Go to **File** → **Export as** → **PNG**.
2. In the export dialog:
   - **Zoom**: Set to 200% for high-resolution output.
   - **Border Width**: Set to 10 for a small margin around the diagram.
   - **Selection Only**: Check this if you only want to export selected shapes.
   - **Shadow**: Check to include drop shadows.
   - **Include a copy of my diagram**: Check this to embed the .drawio XML inside the PNG metadata (allows re-editing later).
3. Click **Export**.
4. Choose a location to save the PNG file.

> *[Screenshot: The PNG export dialog showing all the export options described above.]*

**Exporting as PDF:**
1. Go to **File** → **Export as** → **PDF**.
2. In the export dialog, configure:
   - **Page Size**: Select the desired paper size (e.g., Letter, A4).
   - **Landscape/Portrait**: Choose orientation.
   - **Fit to**: Set how many pages wide and tall the PDF should be.
3. Click **Export**.

> *[Screenshot: The PDF export dialog.]*

**Exporting as SVG (Scalable Vector Graphics):**
1. Go to **File** → **Export as** → **SVG**.
2. This format is ideal for web publishing and maintains crisp quality at any zoom level.

**Exporting to Visio Format (.vsdx):**
1. Go to **File** → **Export as** → **VSDX**.
2. This creates a Microsoft Visio-compatible file that can be opened in Visio or other tools that support the .vsdx format.

> *[Screenshot: The File → Export as submenu showing all available export format options.]*

#### 9.2 Importing from Other Tools

draw.io can import diagrams from other tools:

1. **Import Visio files**: Go to **File** → **Import from** → **Device**, and select a `.vsdx` file.
2. **Import CSV data**: Go to **Extras** → **CSV Import** to generate diagrams automatically from CSV data. This is powerful for creating org charts or network diagrams from spreadsheet data.

**CSV Import Example (Creating an Org Chart from CSV):**

1. Go to **Extras** → **CSV Import**.
2. Paste the following CSV data (or your own):

```
## Summit Outdoor Gear Co. - Organization Chart
## label: %name%<br><i>%role%</i>
## style: shape=mxgraph.basic.rect;rounded=1;fillColor=%fill%;fontColor=#ffffff;strokeColor=none;fontSize=12;
## namespace: csvimport-
## connect: {"from": "manager", "to": "name", "style": "curved=1;endArrow=blockThin;endFill=1;"}
## width: auto
## height: auto
## padding: 15
## ignore: fill,manager
## nodespacing: 40
## levelspacing: 100
## edgespacing: 40
## layout: auto
name,role,fill,manager
Sarah Mitchell,VP of Operations,#1A3C6E,
James Chen,Director of Warehousing,#2E5FA1,Sarah Mitchell
Priya Patel,Director of Shipping & Logistics,#2E5FA1,Sarah Mitchell
Robert Johnson,Director of Customer Service,#2E5FA1,Sarah Mitchell
Maria Lopez,Warehouse Manager - East,#5B8ACF,James Chen
David Kim,Warehouse Manager - West,#5B8ACF,James Chen
Tom Harris,Shipping Manager,#5B8ACF,Priya Patel
Emily Zhang,Logistics Analyst,#5B8ACF,Priya Patel
Angela Davis,CS Team Lead,#5B8ACF,Robert Johnson
```

3. Click **Import**.
4. draw.io will automatically generate a styled organization chart from the CSV data.

> *[Screenshot: The CSV Import dialog with the CSV data pasted in, and the resulting auto-generated organization chart visible on the canvas.]*

This CSV import feature is extremely powerful for business analysts who need to generate diagrams from structured data sources.

#### 9.3 Sharing via Cloud Storage

If your diagram is saved to **Google Drive**:
1. Click the **Share** button in Google Drive.
2. Enter the email addresses of your collaborators.
3. Set permissions (Viewer, Commenter, or Editor).
4. Collaborators can open the shared `.drawio` file directly in draw.io.

If your diagram is saved to **OneDrive**:
1. Open the file in OneDrive and click **Share**.
2. Enter collaborator emails or generate a sharing link.

#### 9.4 Embedding Diagrams in Other Applications

**Embedding in a Webpage:**
1. Go to **Extras** → **Embed** → **HTML**.
2. draw.io generates an HTML snippet that you can paste into any webpage.
3. The embedded diagram is interactive — viewers can zoom and pan.

**Embedding in Confluence:**
1. Install the **draw.io for Confluence** plugin from the Atlassian Marketplace.
2. In a Confluence page, click **"+"** → **draw.io Diagram**.
3. Create or import your diagram directly within Confluence.
4. Save the page — the diagram is embedded and editable inline.

**Embedding in Microsoft Teams:**
1. Install the **draw.io** app from the Microsoft Teams App Store.
2. Use the draw.io tab in a Teams channel to create and share diagrams with your team.

> *[Screenshot: A draw.io diagram embedded inside a Confluence page, showing the inline editing toolbar.]*

---

### Chapter 10: Advanced Features and Tips for Business Analysts

#### 10.1 Using Layers

Layers allow you to organize complex diagrams by placing different categories of elements on separate layers:

1. Go to **View** → **Layers** (or press `Ctrl + Shift + L`) to open the Layers panel.
2. The default layer is called "Background."
3. Click **"+ Add Layer"** to create new layers:
   - **Infrastructure**: For the base network and hardware components.
   - **Applications**: For software services and APIs.
   - **Data Flow**: For arrows and connectors showing data movement.
   - **Annotations**: For text labels, legends, and notes.
4. Select a layer before adding shapes — all new shapes will be placed on the selected layer.
5. Toggle layer visibility by clicking the eye icon next to each layer name.
6. Lock layers by clicking the lock icon to prevent accidental edits.

> *[Screenshot: The Layers panel showing four custom layers with visibility and lock toggles.]*

#### 10.2 Using Custom Shape Libraries

You can create reusable shape libraries for your team:

1. Create commonly used shapes (e.g., your company's logo, standard server icons with specific styling).
2. Select all the shapes you want to save as a library.
3. Go to **File** → **New Library** → Choose a name (e.g., "Summit Standard Shapes").
4. The library appears in the Shape Panel under **"Custom Libraries"** (typically listed under "Scratchpad" at the top).
5. You can share the library file (`.xml`) with teammates.

> *[Screenshot: A custom shape library in the Shape Panel containing company-branded shapes.]*

#### 10.3 Using Tags for Filtering

Tags help you categorize and filter elements in complex diagrams:

1. Select a shape.
2. Go to **Edit** → **Edit Data** (or press `Ctrl + M`).
3. Add a custom property (tag) — for example:
   - Property Name: `department`
   - Value: `warehousing`
4. Use **Edit** → **Find/Replace** to search for shapes with specific tag values.

#### 10.4 Using Page Tabs for Multi-Page Diagrams

draw.io supports multi-page diagrams, similar to spreadsheet tabs:

1. At the bottom of the canvas, you will see a **"+"** button next to the page tab.
2. Click **"+"** to add a new page.
3. Double-click a page tab to rename it (e.g., "Org Chart", "BPMN Process", "System Architecture").
4. Each page is a separate canvas within the same `.drawio` file.

This is ideal for keeping all related diagrams (org chart, process diagram, architecture, ER diagram) in a single file.

> *[Screenshot: The bottom of the draw.io interface showing multiple page tabs labeled "Org Chart," "BPMN Process," "System Architecture," and "ER Diagram."]*

#### 10.5 Keyboard Shortcuts for Efficiency

| Shortcut | Action |
|---|---|
| `Ctrl + S` | Save |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |
| `Ctrl + D` | Duplicate selected shape(s) |
| `Ctrl + Shift + H` | Fit page to screen |
| `Ctrl + A` | Select all |
| `Ctrl + G` | Group selected shapes |
| `Ctrl + Shift + U` | Ungroup |
| `Ctrl + Shift + F` | Find/Replace |
| `Ctrl + M` | Edit metadata/data |
| `Ctrl + E` | Edit style |
| `Ctrl + K` | Insert link |
| `Delete` | Delete selected shape(s) |
| `Alt + Shift + T` | Toggle connection points |

#### 10.6 Tips for Professional-Looking Diagrams

1. **Use consistent colors**: Stick to a color palette. Use your company's brand colors.
2. **Align and distribute**: Use **Format** → **Align** to align shapes. Use **Format** → **Distribute** to evenly space shapes.
3. **Use guides**: Drag from the rulers (top and left edges) to create alignment guides.
4. **Snap to grid**: Enable grid snapping via **View** → **Grid** for consistent spacing.
5. **Use appropriate fonts**: Use sans-serif fonts (like Arial or Helvetica) for readability.
6. **Add a title and legend**: Every diagram should have a clear title and a legend explaining symbols and colors.
7. **Keep it simple**: Avoid cluttering diagrams with too much detail. Use multiple pages or layers for complex systems.

---

## Part 4: Best Additional Tutorial Materials

### Online Tutorials and Documentation

1. **Official draw.io Documentation**
   - URL: [https://www.drawio.com/doc/](https://www.drawio.com/doc/)
   - Description: The official documentation covers all features, from basic usage to advanced topics like custom libraries, plugins, and integrations.

2. **draw.io Blog and Tutorials**
   - URL: [https://www.drawio.com/blog](https://www.drawio.com/blog)
   - Description: The official blog contains tutorials, tips, and announcements about new features.

3. **draw.io YouTube Channel**
   - URL: [https://www.youtube.com/channel/UCkfBPJA8bWBxjwsGXpesibA](https://www.youtube.com/channel/UCkfBPJA8bWBxjwsGXpesibA)
   - Description: Video tutorials covering a wide range of draw.io features and use cases.

4. **"Getting Started with draw.io" Tutorial**
   - URL: [https://www.drawio.com/doc/getting-started-editor](https://www.drawio.com/doc/getting-started-editor)
   - Description: A beginner-friendly guide to the draw.io editor interface and basic operations.

5. **BPMN 2.0 Diagramming with draw.io**
   - URL: [https://www.drawio.com/blog/bpmn-2-0](https://www.drawio.com/blog/bpmn-2-0)
   - Description: Specific tutorial on creating BPMN 2.0 process diagrams in draw.io.

6. **draw.io for Confluence Documentation**
   - URL: [https://www.drawio.com/doc/drawio-confluence-cloud](https://www.drawio.com/doc/drawio-confluence-cloud)
   - Description: How to use the draw.io plugin within Atlassian Confluence for team collaboration.

7. **draw.io GitHub Repository**
   - URL: [https://github.com/jgraph/drawio](https://github.com/jgraph/drawio)
   - Description: The open-source repository for draw.io, useful for developers who want to extend or customize the tool.

### Tutorial Books

1. **"Business Process Management: Concepts, Languages, Architectures"**
   - Authors: Mathias Weske
   - Publisher: Springer
   - ISBN: 978-3-662-59431-5
   - Description: While not draw.io-specific, this book provides an excellent foundation for BPMN and business process modeling, which are key use cases for draw.io.

2. **"BPMN Method and Style, 2nd Edition"**
   - Author: Bruce Silver
   - Publisher: Cody-Cassidy Press
   - ISBN: 978-0-982-36841-7
   - Description: The definitive guide to using BPMN notation correctly and effectively. Essential reading for business analysts using draw.io's BPMN features.

3. **"UML Distilled: A Brief Guide to the Standard Object Modeling Language, 3rd Edition"**
   - Author: Martin Fowler
   - Publisher: Addison-Wesley Professional
   - ISBN: 978-0-321-19368-1
   - Description: A concise guide to UML notation, useful for creating UML diagrams in draw.io.

4. **"Information Architecture: For the Web and Beyond, 4th Edition"**
   - Authors: Louis Rosenfeld, Peter Morville, Jorge Arango
   - Publisher: O'Reilly Media
   - ISBN: 978-1-491-91168-6
   - Description: Covers information architecture concepts that are useful for designing sitemaps, user flows, and wireframes in draw.io.

5. **"Fundamentals of Database Systems, 7th Edition"**
   - Authors: Ramez Elmasri, Shamkant B. Navathe
   - Publisher: Pearson
   - ISBN: 978-0-133-97077-7
   - Description: Comprehensive guide to database design including ER modeling, which is covered in Chapter 6 of this tutorial.

### Additional Resources

- **draw.io Shortcuts Cheat Sheet**: [https://www.drawio.com/blog/shortcuts](https://www.drawio.com/blog/shortcuts)
- **draw.io Template Gallery**: Built into the application via **File** → **New** → Browse templates.
- **draw.io Community Forum**: [https://groups.google.com/g/drawio](https://groups.google.com/g/drawio) — Ask questions and share tips with other draw.io users.
- **Atlassian Marketplace (draw.io plugin)**: [https://marketplace.atlassian.com/apps/1210933/draw-io-diagrams-for-confluence](https://marketplace.atlassian.com/apps/1210933/draw-io-diagrams-for-confluence)

---

## Appendix A: Summary of Diagrams Created in This Tutorial

| # | Diagram | Filename | Diagram Type | Purpose |
|---|---|---|---|---|
| 1 | Organization Chart | `Summit_OrgChart.drawio` | Org Chart | Visualize department structure and reporting relationships |
| 2 | Order Fulfillment Process | `Summit_OrderFulfillment_BPMN.drawio` | BPMN 2.0 Process Diagram | Document end-to-end order fulfillment workflow |
| 3 | System Architecture | `Summit_SystemArchitecture.drawio` | Architecture Diagram | Show technology components and their interactions |
| 4 | Database ER Diagram | `Summit_ERDiagram.drawio` | Entity-Relationship Diagram | Model the database schema for the order system |
| 5 | Customer Journey Map | `Summit_CustomerJourneyMap.drawio` | Customer Journey Map | Track customer experience across purchase stages |
| 6 | Network Infrastructure | `Summit_NetworkDiagram.drawio` | Network/Cloud Diagram | Document AWS cloud infrastructure and security |

## Appendix B: Glossary of Terms

| Term | Definition |
|---|---|
| **BPMN** | Business Process Model and Notation — a standardized notation for modeling business processes |
| **Swim Lane** | A visual element in BPMN that shows which department or role is responsible for each activity |
| **Gateway** | A BPMN element representing a decision point or branching/merging of process flows |
| **Sequence Flow** | A solid arrow in BPMN showing the order of activities |
| **Message Flow** | A dashed arrow in BPMN showing communication between different pools (departments) |
| **ER Diagram** | Entity-Relationship Diagram — a visual model of a database schema |
| **Crow's Foot Notation** | A notation style for ER diagrams using "crow's foot" symbols to show relationship cardinality |
| **UML** | Unified Modeling Language — a standardized notation for modeling software systems |
| **VPC** | Virtual Private Cloud — an isolated network environment in AWS |
| **CDN** | Content Delivery Network — a distributed network for fast content delivery |
| **API Gateway** | A service that acts as a single entry point for API requests |
| **Auto Scaling** | Automatically adjusting the number of server instances based on demand |

---

*This tutorial was created for BIT 4454: Business Analysis Seminar in IT. The example case (Summit Outdoor Gear Co. order fulfillment system) is a novel business application created specifically for this tutorial and is directly applicable to e-commerce and supply chain team projects.*
