# Copilot Instructions for projeto-login

## Project Overview
This is a simple static HTML/CSS project for a login page, part of a study/learning project. It's a basic frontend-only application with no JavaScript, backend, or build system.

## Architecture
- **Structure**: Flat file structure with `index.html` in root, `estilos/style.css` for styles, and `imagens/` for images.
- **Components**: Single page with a login form containing username/password inputs and submit button.
- **Data Flow**: Form submits via POST to `/login` (no backend implemented).

## Key Conventions
- **Language**: All content and comments in Portuguese (pt-BR).
- **Naming**: Use Portuguese for class names, IDs, and labels (e.g., `login-section`, `login-form`).
- **Styling**: Color palette defined in CSS comments at the top of `style.css`. Use these colors consistently.
- **File Organization**:
  - CSS files in `estilos/` directory
  - Images in `imagens/` directory
  - HTML files in root

## Development Workflow
- **Running the Project**: Open `index.html` directly in a web browser. No server required.
- **Editing**: Modify HTML in `index.html`, styles in `estilos/style.css`.
- **No Build/Tests**: This is a static project with no compilation, testing, or deployment scripts.

## Patterns to Follow
- **HTML Structure**: Use semantic elements like `<main>`, `<section>`, `<form>` with proper labels and accessibility attributes.
- **Form Handling**: Keep forms simple; no client-side validation implemented.
- **Styling**: Apply styles directly in `style.css`; no preprocessors or frameworks.

## Key Files
- `index.html`: Main login page
- `estilos/style.css`: All styles, including color palette comments
- `README.md`: Basic project description