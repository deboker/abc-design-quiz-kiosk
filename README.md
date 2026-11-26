
# ABC Design – Interactive Quiz Kiosk

An interactive touchscreen quiz application developed for exhibitions, trade fairs and promotional events.

The application combines visitor engagement, lead generation and data collection through a dedicated tablet-based interface.

Built with React 19, TypeScript, Vite 8 and Firebase.

**[Visit Live Application](https://abc-design-quiz-kiosk.web.app/)**

<img width="2896" height="1568" alt="SCR-20261126-qnkv" src="https://github.com/user-attachments/assets/668f9dbb-91c5-462f-ba67-165c2f107949" />


## Project Overview

ABC Design Quiz Kiosk is a specialized web application designed for interactive use at trade fairs and exhibitions.

Visitors complete a six-question quiz, provide their contact information and submit their responses to the ABC Design team.

The application includes an internal administration interface for reviewing submissions and exporting collected data.

## Key Features

- Interactive six-question quiz
- Tablet-optimized touchscreen interface
- Contact information collection
- Data processing consent
- Form validation
- Animated screen transitions
- Automatic reset after inactivity
- Cloud Firestore data storage
- Restricted administration interface
- Quiz response management
- CSV data export
- Firebase Hosting deployment

## Application Preview

### Quiz Interface

<img width="2946" height="1646" alt="SCR-20261126-qntc" src="https://github.com/user-attachments/assets/dce54363-8d21-4fab-8b60-f65b962e8bc3" />


### Administration Dashboard

<img width="1385" height="896" alt="SCR-20261126-qobm" src="https://github.com/user-attachments/assets/73baa802-dd4e-4b6a-8d22-c38bed2fa011" />


## Application Workflow

1. The visitor starts the interactive quiz.
2. The visitor answers six questions.
3. The visitor completes the contact form.
4. The visitor confirms consent to data processing.
5. Quiz responses and contact information are stored in Cloud Firestore.
6. Authorized administrators can review submissions and export records to CSV.
7. After inactivity, the kiosk automatically returns to its initial screen.

## Technology Stack

| Technology | Purpose |
|---|---|
| React 19 | User interface and application state |
| TypeScript | Type-safe application development |
| Vite 8 | Development and production build tooling |
| React Hook Form | Form handling and input validation |
| Framer Motion | Animations and screen transitions |
| Cloud Firestore | Quiz responses and contact data storage |
| Firebase Hosting | Cloud deployment and hosting |
| CSS | Custom touchscreen-oriented styling |
| Git & GitHub | Version control and project documentation |

## Use Cases

- Trade fairs and exhibitions
- Interactive marketing campaigns
- Visitor engagement
- Lead generation
- Corporate events
- Digital touchscreen kiosks
- Customer questionnaires

## Development Focus

- Modern React and TypeScript development
- Interactive application workflows
- Touchscreen user experience
- Tablet-optimized interface design
- Form validation and data collection
- Cloud database integration
- Administration interface development
- Automated kiosk reset behavior
- Data export functionality
- Cloud deployment

## Build & Deployment

The application uses Vite for production builds:

```bash
npm run build
```

The production application is deployed through Firebase Hosting:

```bash
firebase deploy --only hosting
```

## Project Status

Live web application designed for interactive event experiences and business lead collection.

Administrative functionality is restricted to authorized users.

## Source Code

This repository serves as a public portfolio showcase.

The original application source code is maintained separately and is not publicly available.

## Developer

**Andrej Andrasik**

Frontend Developer | React | Next.js | TypeScript | JavaScript | WordPress

- [Portfolio](https://portfolio-andrey-new.netlify.app/)
- [GitHub](https://github.com/deboker)
- [Live Application](https://abc-design-quiz-kiosk.web.app/)
