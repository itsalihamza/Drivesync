# DriveSync Project Asset Classification

## Asset Classification Table

| Asset Name | Status | Notes |
|------------|---------|-------|
| **Core Components** |
| `/client/src/App.jsx` | Active | Main application and routing handler |
| `/client/src/components/` | Active | Core UI components organized by feature |
| `AuthContext.jsx` | Active | Global authentication state management |
| `ProfileSetupContext.jsx` | Active | Profile setup workflow management |
| `theme.js` | Active | Global styling configuration |
| **Backend Core** |
| `/server/src/app.js` | Active | Main server application |
| `/server/src/config/` | Active | Server configuration (DB, Auth, Keys) |
| `/server/src/routes/` | Active | API route definitions |
| `/server/src/controllers/` | Active | Business logic handlers |
| **Services** |
| `accountService.js` | Active | Account management operations |
| `analyticsService.js` | Active | Data analytics and reporting |
| `geminiService.js` | Active | AI/ML integration service |
| `mailService.js` | Active | Email notification system |
| `notificationService.js` | Partially Active | Email active, SMS commented out |
| **Authentication** |
| `authService.js` | Active | Core authentication logic |
| `deviceService.js` | Active | Device tracking and management |
| **Vehicle Management** |
| `vehicleService.js` | Active | Vehicle inventory operations |
| `VehicleDetailPage.jsx` | Active | Vehicle information display |
| **Payment & Transactions** |
| `paymentService.js` | Active | Payment processing integration |
| `transactionService.js` | Active | Transaction management |
| `quotationService.js` | Active | Quote generation and management |
| **Testing** |
| `/client/src/__tests__/` | Reusable | Frontend test suites |
| `/server/tests/` | Reusable | Backend API tests |
| `auth-endpoints.json` | Reusable | Auth endpoint test definitions |
| **Documentation** |
| `/README.md` | Active | Main project documentation |
| `/client/README.md` | Active | Frontend-specific documentation |
| **Configuration** |
| `tailwind.config.js` | Active | Tailwind CSS configuration |
| `postcss.config.js` | Active | PostCSS build configuration |
| **Static Assets** |
| `/public/images/` | Active | Image assets (cars, testimonials) |
| `/client/src/components/auth/OldLoginForm.jsx` | Deprecated | Replaced by new authentication flow |
| `/client/src/components/auth/LoginForm.jsx` | Active | Current authentication implementation |
| `/client/src/utils/oldValidation.js` | Deprecated | Legacy validation methods |
| `/client/src/utils/validation.js` | Active | Current validation utilities |
| `/client/src/components/common/Button` | Reusable | Shared button components |
| `/client/src/hooks/useForm.js` | Reusable | Form handling hook |
| `/client/src/utils/formatters.js` | Reusable | Data formatting utilities |
| `/server/src/utils/validators.js` | Reusable | Server-side validation utilities |
| `/server/src/middleware/auth.js` | Active | Authentication middleware |
| `/client/src/services/api.js` | Active | API service layer |
| `/server/src/config/database.js` | Active | Database configuration |
| `/server/tests/helpers.js` | Reusable | Test utility functions |

## Status Definitions
- **Active**: Currently in use and fully functional components
- **Deprecated**: Legacy components that are being phased out or replaced
- **Reusable**: Generic, shared components and utilities that can be used across the application

## Project Metrics
- Total Lines of Code (Server): 10,961
- Source Code Lines: 9,013
- Comments: 897
- File Types: 
  - JavaScript: 10,935 lines
  - Jade: 18 lines
  - CSS: 8 lines

## Status Definitions
- **Active**: Currently in use and fully functional
- **Partially Active**: Partially implemented or pending features
- **Reusable**: Components that can be reused across the application
- **Frontend**:
  - React.js
  - Tailwind CSS
  - Material-UI Components
  - Chart.js for Analytics
  - Framer Motion for Animations
  - React Router for Navigation
  - Axios for API Communication

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB with Mongoose
  - JWT Authentication
  - Multer for File Uploads
  - Passport.js for Social Auth


