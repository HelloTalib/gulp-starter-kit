# **Gulp Starter Kit**
Kickstart your project with this Gulp-based workflow.

---

## **Getting Started**

### **Step 1: Clone or Download the Repository**
Clone this repository into your local project directory:

```bash
git clone https://github.com/HelloTalib/gulp-starter-kit.git
```

Alternatively, download the repository and extract it to a folder.

---

### **Step 2: Install Dependencies**

Navigate to your project directory and run the following command to install all dependencies:

```bash
npm install
```

#### **Required Packages**

| Package                | Installation Command                                        | Notes                           |
|------------------------|------------------------------------------------------------|---------------------------------|
| **Gulp CLI**           | `npm install --global gulp-cli`                            | Installs the global Gulp CLI   |
| **Gulp Sass**          | `npm install sass gulp-sass --save-dev`                    | For SCSS compilation           |
| **Browser Sync**       | `npm install --global browser-sync`                        | Enables live-reload server     |
| **Gulp Autoprefixer**  | `npm install --save-dev gulp-autoprefixer`                 | Adds vendor prefixes to CSS    |

---

## **Running the Project**

### **Start the Development Server**

Use the following command to start the development server:

```bash
gulp start
```

This command will:
- Watch your project files for changes.
- Compile your SCSS/CSS files.
- Automatically reload your browser with **Browser Sync**.
