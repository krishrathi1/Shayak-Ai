<<<<<<< HEAD
# Sahayak AI - AI-Powered Educational Assistant

<div align="center">
  <img src="public/image.png" alt="Sahayak AI Logo" width="200"/>
  
  [![Next.js](https://img.shields.io/badge/Next.js-15.3.3-black)](https://nextjs.org/)
  [![React](https://img.shields.io/badge/React-18.3.1-blue)](https://reactjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue)](https://www.typescriptlang.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC)](https://tailwindcss.com/)
  [![Firebase](https://img.shields.io/badge/Firebase-11.9.1-orange)](https://firebase.google.com/)
  [![Genkit AI](https://img.shields.io/badge/Genkit_AI-1.14.1-purple)](https://genkit.ai/)
</div>

## 🎯 Project Overview

**Sahayak AI** is a comprehensive AI-powered educational platform designed to revolutionize teaching and learning experiences. The platform provides teachers with intelligent tools to create engaging content, manage classrooms, and enhance student learning outcomes through cutting-edge AI technology.

## 🚀 MVP (Minimum Viable Product)

### Core Features Delivered:

#### 1. **AI-Powered Content Creation**
   - **Photo-to-Worksheet Conversion**: Instantly convert textbook pages into interactive worksheets using computer vision and AI text extraction
   - **Custom Worksheet Generation**: Create worksheets from scratch with multiple question types (MCQ, fill-in-the-blanks, short answer)
   - **Multi-language Content Creation**: Generate stories, poems, and educational content in 8+ languages (English, Hindi, Bengali, Bhojpuri, Tamil, Telugu, Kannada, Spanish, French)
   - **Visual Aids Generation**: Create blackboard-style line drawings and illustrations for educational concepts
   - **Presentation Slides Generation**: Automatically generate presentation content with structured slides
   - **AI Video Generation**: Create educational videos using Google's Veo 3 technology with customizable duration (5-25 seconds)

#### 2. **Smart Classroom Management**
   - **Face Recognition Attendance**: AI-powered student identification using computer vision and facial recognition
   - **Student Roster Management**: Upload and manage student photos with names for attendance tracking
   - **Grade Tracking & Analytics**: Comprehensive student progress monitoring with visual charts and reports
   - **Calendar & Scheduling**: School calendar management with lesson scheduling and event organization
   - **QR Code Generation**: Create QR codes for answer keys and educational resources

#### 3. **Educational AI Assistant (Ask Sahayak)**
   - **Kid-friendly Explanations**: Grade-level adapted explanations for complex topics using advanced language models
   - **Text-to-Speech**: Convert explanations to audio for accessibility and multi-modal learning
   - **Speech Recognition**: Hands-free interaction with voice input support
   - **Multi-language Support**: Full interface and content support in English, Hindi, Bengali, and Bhojpuri
   - **Interactive Q&A**: Real-time question answering with contextual understanding

#### 4. **Assessment & Evaluation Tools**
   - **AI Quiz Generator**: Create quizzes on any topic with multiple question types (multiple-choice, true/false, short-answer)
   - **Rubric Creator**: Generate detailed grading rubrics for assignments with specific criteria
   - **Writing Assistant**: Provide grammar, spelling, and style feedback for student writing
   - **Discussion Generator**: Create engaging classroom discussion topics and materials
   - **Content Adaptation**: Adjust text complexity for different grade levels

#### 5. **Professional Development & Resources**
   - **Teacher Skill Development**: Personalized learning plans with actionable strategies and resources
   - **Educational Video Library**: Curated YouTube videos filtered by grade and subject
   - **Mentorship Planning**: Create individualized mentorship plans for student support
   - **Lesson Planning**: AI-generated detailed lesson plans with activities, materials, and timing
   - **Professional Growth Roadmaps**: Structured development plans with YouTube resource integration

## 🎯 Problems Solved

### For Teachers:
- **Time Management**: Automates repetitive tasks like attendance, worksheet creation, and grading
- **Content Creation**: Generates high-quality educational materials in seconds
- **Language Barriers**: Supports multiple languages for diverse classrooms
- **Resource Scarcity**: Provides access to digital textbooks and question banks
- **Professional Growth**: Offers personalized development plans and resources

### For Students:
- **Learning Accessibility**: Kid-friendly explanations for complex topics
- **Engagement**: Interactive content and visual aids
- **Personalized Support**: Individual mentorship plans
- **Multi-modal Learning**: Text, audio, and visual content

### For Educational Institutions:
- **Cost Efficiency**: Reduces need for expensive educational software
- **Scalability**: Can serve multiple classrooms and subjects
- **Data Insights**: Comprehensive analytics and progress tracking
- **Modernization**: Brings AI-powered tools to traditional education

## 🛠️ Technology Stack

### Frontend Architecture
- **Next.js 15.3.3** - React framework with App Router for server-side rendering and API routes
- **React 18.3.1** - Modern React with concurrent features and hooks
- **TypeScript 5.0** - Static type checking and enhanced developer experience
- **Tailwind CSS 3.4.1** - Utility-first CSS framework with custom design system
- **Radix UI** - Accessible, unstyled component primitives for building design systems
- **Lucide React** - Beautiful, customizable icon library
- **React Hook Form** - Performant forms with easy validation
- **Zod** - TypeScript-first schema validation
- **Recharts** - Composable charting library for analytics

### AI & Machine Learning
- **Genkit AI 1.14.1** - Google's AI framework for building intelligent applications with flows and prompts
- **Google AI (Gemini)** - Advanced language models for text generation, analysis, and reasoning
- **Google Veo 3** - State-of-the-art AI video generation technology
- **Cohere AI 7.18.0** - Enterprise-grade text generation and analysis
- **ChromaDB** - Vector database for AI embeddings and semantic search
- **Computer Vision APIs** - For image analysis and facial recognition

### Backend & Infrastructure
- **Firebase 11.9.1** - Complete backend-as-a-service platform
  - **Firestore** - NoSQL cloud database for real-time data
  - **Firebase Auth** - User authentication and authorization
  - **Firebase Storage** - File storage for images and documents
  - **Firebase Admin SDK** - Server-side Firebase operations
- **Next.js API Routes** - Serverless API endpoints
- **Vercel** - Deployment and hosting platform

### Audio & Media Processing
- **Web Speech API** - Browser-based speech recognition and synthesis
- **Text-to-Speech Services** - Multi-language audio generation
- **QR Code Generation** - Dynamic QR codes for educational resources
- **Image Processing** - Real-time image analysis and manipulation

### Development & Quality Tools
- **ESLint** - Code linting and style enforcement
- **Prettier** - Code formatting
- **TypeScript** - Static type checking
- **Turbopack** - Fast bundler for development
- **PostCSS** - CSS processing and optimization

## 📁 Project Structure

```
sahayakai/
├── src/
│   ├── app/                           # Next.js App Router pages
│   │   ├── ask-sahayak/               # AI tutor interface with speech recognition
│   │   ├── attendance/                # Face recognition attendance system
│   │   ├── calendar/                  # School calendar and scheduling
│   │   ├── content-creator/           # Multi-language content generation
│   │   ├── content-adaptation/        # Grade-level content adjustment
│   │   ├── dashboard/                 # Main application dashboard
│   │   ├── discussion-generator/      # Classroom discussion topics
│   │   ├── grade-tracking/            # Student progress analytics
│   │   ├── lesson-planner/            # AI lesson plan generation
│   │   ├── mentoring/                 # Student mentorship planning
│   │   ├── photo-to-worksheet/        # Textbook to worksheet conversion
│   │   ├── presentation-creator/      # AI presentation generation
│   │   ├── qr-code-generator/         # QR code creation for resources
│   │   ├── quiz-generator/            # Automated quiz creation
│   │   ├── rubric-creator/            # Grading rubric generation
│   │   ├── smart-class/               # Educational video library
│   │   ├── student-roster/            # Student management system
│   │   ├── teacher-professional-development/ # Teacher skill development
│   │   ├── textbooks/                 # Digital textbook library
│   │   ├── video-generator/           # AI video creation with Veo 3
│   │   ├── visual-aids-generator/     # Educational illustration creation
│   │   ├── worksheet-creator/         # Custom worksheet generation
│   │   ├── writing-assistant/         # Writing feedback and improvement
│   │   ├── api/                       # API routes and server actions
│   │   ├── globals.css                # Global styles and Tailwind config
│   │   ├── layout.tsx                 # Root layout component
│   │   └── page.tsx                   # Homepage with feature grid
│   ├── ai/
│   │   ├── flows/                     # Genkit AI workflows
│   │   │   ├── ask-sahayak.ts         # Kid-friendly explanations
│   │   │   ├── photo-to-worksheet.ts  # Image to worksheet conversion
│   │   │   ├── generate-video.ts      # Veo 3 video generation
│   │   │   ├── recognize-students.ts  # Face recognition for attendance
│   │   │   ├── create-lesson-plan.ts  # Lesson planning AI
│   │   │   ├── generate-quiz.ts       # Quiz generation
│   │   │   ├── teacher-pd.ts          # Professional development plans
│   │   │   ├── generate-localized-content.ts # Multi-language content
│   │   │   ├── create-worksheet.ts    # Custom worksheet creation
│   │   │   ├── create-rubric.ts       # Grading rubric generation
│   │   │   ├── create-presentation.ts # Presentation slides
│   │   │   ├── generate-discussion.ts # Discussion topics
│   │   │   ├── create-mentorship-plan.ts # Student mentorship
│   │   │   ├── enhance-writing.ts     # Writing improvement
│   │   │   ├── generate-visual-aid.ts # Educational illustrations
│   │   │   ├── adapt-content-grade-level.ts # Content adaptation
│   │   │   ├── text-to-speech.ts      # Audio generation
│   │   │   ├── search-youtube-videos.ts # Video curation
│   │   │   ├── generate-answer-key-qr-code.ts # QR code generation
│   │   │   └── *.types.ts             # TypeScript type definitions
│   │   ├── genkit.ts                  # Genkit AI configuration
│   │   └── dev.ts                     # Development server setup
│   ├── components/
│   │   ├── ui/                        # Radix UI component primitives
│   │   │   ├── button.tsx             # Button components
│   │   │   ├── card.tsx               # Card components
│   │   │   ├── dialog.tsx             # Modal dialogs
│   │   │   ├── form.tsx               # Form components
│   │   │   ├── input.tsx              # Input fields
│   │   │   ├── select.tsx             # Select dropdowns
│   │   │   ├── textarea.tsx           # Text area components
│   │   │   ├── toast.tsx              # Toast notifications
│   │   │   └── ...                    # Other UI components
│   │   ├── language-switcher.tsx      # Multi-language interface
│   │   └── icons.tsx                  # Custom icon components
│   ├── contexts/
│   │   └── language-context.tsx       # Language switching context
│   ├── hooks/
│   │   ├── use-auth.tsx               # Authentication hooks
│   │   ├── use-mobile.tsx             # Mobile detection
│   │   ├── use-speech-recognition.ts  # Speech recognition
│   │   └── use-toast.ts               # Toast notification hooks
│   ├── lib/
│   │   ├── actions.ts                 # Server actions
│   │   ├── firebase-config.ts         # Firebase configuration
│   │   ├── utils.ts                   # Utility functions
│   │   └── ...                        # Other library functions
│   └── locales/                       # Internationalization
│       ├── en.json                    # English translations
│       ├── hi.json                    # Hindi translations
│       ├── bn.json                    # Bengali translations
│       └── bho.json                   # Bhojpuri translations
├── public/                            # Static assets
│   ├── image.png                      # Application logo
│   └── ...                            # Other static files
├── package.json                       # Dependencies and scripts
├── tailwind.config.ts                 # Tailwind CSS configuration
├── tsconfig.json                      # TypeScript configuration
├── next.config.ts                     # Next.js configuration
├── firebase.json                      # Firebase configuration
├── firestore.rules                    # Firestore security rules
└── README.md                          # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- **Node.js 18+** (LTS version recommended)
- **npm 9+** or **yarn 1.22+**
- **Git** for version control
- **Firebase project** with Firestore, Storage, and Auth enabled
- **Google AI API access** (Gemini and Veo 3)
- **Cohere AI API key** for additional text generation capabilities

### System Requirements
- **RAM**: Minimum 8GB, Recommended 16GB
- **Storage**: At least 2GB free space
- **Network**: Stable internet connection for AI services
- **Browser**: Modern browser with Web Speech API support (Chrome, Firefox, Safari, Edge)

### Installation Guide

#### 1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd sahayakai
   ```

#### 2. **Install Dependencies**
   ```bash
   # Using npm
   npm install
   
   # Using yarn
   yarn install
   ```

#### 3. **Environment Configuration**
   Create a `.env.local` file in the root directory:
   ```env
   # Firebase Configuration
   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
   NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
   NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=123456789
   NEXT_PUBLIC_FIREBASE_APP_ID=1:123456789:web:abcdef123456

   # AI Services Configuration
   GOOGLE_AI_API_KEY=your_google_ai_api_key
   GOOGLE_GENERATIVE_AI_API_KEY=your_gemini_api_key
   COHERE_API_KEY=your_cohere_api_key

   # Firebase Admin SDK (for server-side operations)
   FIREBASE_ADMIN_PROJECT_ID=your_project_id
   FIREBASE_ADMIN_PRIVATE_KEY="-----BEGIN PRIVATE KEY-----\nYour Private Key\n-----END PRIVATE KEY-----\n"
   FIREBASE_ADMIN_CLIENT_EMAIL=firebase-adminsdk-xxxxx@your_project.iam.gserviceaccount.com

   # Optional: Development Configuration
   NODE_ENV=development
   NEXT_PUBLIC_APP_URL=http://localhost:9002
   ```

#### 4. **Firebase Setup**
   1. Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)
   2. Enable Authentication (Email/Password, Google)
   3. Create a Firestore database in production mode
   4. Set up Firebase Storage with security rules
   5. Download service account key for admin SDK

#### 5. **Google AI Setup**
   1. Visit [Google AI Studio](https://aistudio.google.com/)
   2. Create an API key for Gemini and Veo 3
   3. Enable necessary APIs in Google Cloud Console
   4. Set up billing for API usage

#### 6. **Cohere AI Setup**
   1. Sign up at [Cohere AI](https://cohere.ai/)
   2. Generate an API key
   3. Configure usage limits and billing

#### 7. **Start Development Servers**
   ```bash
   # Terminal 1: Start Next.js development server
   npm run dev
   
   # Terminal 2: Start Genkit AI development server
   npm run genkit:dev
   
   # Terminal 3: Start Genkit with file watching (optional)
   npm run genkit:watch
   ```

#### 8. **Access the Application**
   - **Main Application**: http://localhost:9002
   - **Genkit AI Server**: http://localhost:4000 (default)
   - **API Documentation**: Available in `/docs` folder

### Development Workflow

#### **Code Quality Checks**
   ```bash
   # Type checking
   npm run typecheck
   
   # Linting
   npm run lint
   
   # Format code
   npx prettier --write .
   ```

#### **Testing AI Flows**
   ```bash
   # Test specific AI flow
   npx genkit run src/ai/flows/ask-sahayak.ts
   
   # Test with sample data
   npx genkit run src/ai/flows/photo-to-worksheet.ts --input sample-data.json
   ```

#### **Database Management**
   ```bash
   # View Firestore data
   firebase firestore:get /collection
   
   # Export data
   firebase firestore:export ./backup
   
   # Import data
   firebase firestore:import ./backup
   ```

## 🎨 Features in Detail

### 🤖 Ask Sahayak - AI Educational Assistant
**Core Functionality**: Provides grade-appropriate explanations for complex topics using advanced language models.

**Technical Implementation**:
- **AI Model**: Google Gemini with custom prompts for educational content
- **Grade Adaptation**: Content complexity automatically adjusted based on grade level (K-12)
- **Multi-language Support**: 8+ languages including English, Hindi, Bengali, Bhojpuri, Tamil, Telugu, Kannada, Spanish, French
- **Speech Recognition**: Browser-based Web Speech API for hands-free interaction
- **Text-to-Speech**: Real-time audio generation for accessibility and multi-modal learning
- **Contextual Understanding**: Maintains conversation context for follow-up questions

**Use Cases**:
- Explaining scientific concepts to elementary students
- Breaking down complex mathematical problems
- Providing historical context in simple terms
- Supporting students with learning disabilities through audio

### 📸 Photo-to-Worksheet - Computer Vision Integration
**Core Functionality**: Converts textbook pages into interactive worksheets using AI image analysis.

**Technical Implementation**:
- **Computer Vision**: Google AI Vision API for text extraction from images
- **AI Processing**: Genkit flows for intelligent question generation
- **Question Types**: Multiple choice, fill-in-the-blanks, short answer, true/false
- **Answer Key Generation**: Automatic answer creation with QR code integration
- **Difficulty Scaling**: Adjustable complexity based on grade level
- **Format Support**: JPG, PNG, PDF processing capabilities

**Use Cases**:
- Converting physical textbooks to digital worksheets
- Creating practice materials from existing resources
- Generating homework assignments from class materials
- Supporting remote learning with digital content

### 👥 Smart Attendance - Facial Recognition System
**Core Functionality**: Automated student attendance using AI-powered facial recognition.

**Technical Implementation**:
- **Face Recognition**: Advanced computer vision algorithms for student identification
- **Student Database**: Firebase Storage for secure photo management
- **Real-time Processing**: Live camera feed analysis for instant recognition
- **Privacy Compliance**: Local processing with optional cloud backup
- **Attendance Analytics**: Comprehensive reporting and tracking
- **Multi-class Support**: Separate rosters for different classes

**Use Cases**:
- Automated daily attendance tracking
- Substitute teacher support with student identification
- Parent communication with attendance reports
- Administrative reporting and compliance

### 📚 Content Creation Suite - Multi-language AI Generation
**Core Functionality**: Generates educational content in multiple languages and formats.

**Technical Implementation**:
- **Multi-language AI**: Genkit flows with language-specific prompts
- **Content Types**: Stories, poems, explanations, lesson materials
- **Grade Adaptation**: Content complexity matching target grade levels
- **Cultural Sensitivity**: Region-specific content and examples
- **Quality Assurance**: AI-powered content review and improvement
- **Export Options**: PDF, Word, and digital formats

**Supported Languages**:
- **English**: Primary interface and content
- **Hindi**: हिंदी - Indian national language
- **Bengali**: বাংলা - West Bengal and Bangladesh
- **Bhojpuri**: भोजपुरी - Eastern India
- **Tamil**: தமிழ் - Tamil Nadu
- **Telugu**: తెలుగు - Andhra Pradesh and Telangana
- **Kannada**: ಕನ್ನಡ - Karnataka
- **Spanish**: Español - International support
- **French**: Français - International support

### 📊 Assessment Tools - AI-Powered Evaluation
**Core Functionality**: Comprehensive assessment and evaluation tools for teachers.

**Technical Implementation**:
- **Quiz Generator**: AI-powered question creation with multiple formats
- **Rubric Creator**: Detailed grading criteria with customizable scales
- **Writing Assistant**: Grammar, style, and content feedback
- **Discussion Generator**: Engaging classroom discussion topics
- **Content Adaptation**: Text complexity adjustment for different grades
- **Analytics Dashboard**: Student performance tracking and insights

**Assessment Types**:
- **Multiple Choice**: 4-option questions with automatic grading
- **True/False**: Binary questions for quick assessment
- **Short Answer**: Open-ended questions with AI evaluation
- **Essay Questions**: Detailed writing assessment with feedback
- **Project Rubrics**: Comprehensive evaluation criteria

### 🎓 Professional Development - Teacher Growth Platform
**Core Functionality**: Personalized professional development plans and resources.

**Technical Implementation**:
- **Learning Paths**: AI-generated personalized development plans
- **Resource Curation**: YouTube video filtering by topic and expertise level
- **Skill Assessment**: Self-evaluation tools for teacher competencies
- **Mentorship Planning**: Individual student support strategies
- **Progress Tracking**: Development milestone monitoring
- **Community Features**: Teacher collaboration and sharing

**Development Areas**:
- **Classroom Management**: Behavior management and engagement strategies
- **Technology Integration**: Digital tools and AI in education
- **Assessment Methods**: Modern evaluation techniques
- **Inclusive Education**: Special needs and diverse learning support
- **Subject Expertise**: Content-specific teaching methodologies

### 🎬 AI Video Generation - Veo 3 Integration
**Core Functionality**: Creates educational videos using Google's latest Veo 3 technology.

**Technical Implementation**:
- **Veo 3 API**: State-of-the-art AI video generation
- **Customizable Parameters**: Duration (5-25 seconds), aspect ratio, style, quality
- **Script Generation**: AI-powered video script creation
- **Safety Filters**: Content moderation and educational appropriateness
- **Export Options**: Multiple formats and resolutions
- **Batch Processing**: Multiple video generation capabilities

**Video Types**:
- **Concept Explanations**: Visual demonstrations of complex topics
- **Story Narratives**: Educational storytelling
- **Process Demonstrations**: Step-by-step instructional videos
- **Interactive Elements**: Videos with embedded questions and activities

### 📈 Analytics & Reporting - Data-Driven Insights
**Core Functionality**: Comprehensive analytics for student and teacher performance.

**Technical Implementation**:
- **Real-time Dashboards**: Live data visualization with Recharts
- **Student Progress Tracking**: Individual and class-level analytics
- **Attendance Analytics**: Pattern recognition and reporting
- **Assessment Insights**: Performance trends and improvement areas
- **Export Capabilities**: PDF and Excel report generation
- **Privacy Compliance**: FERPA and GDPR compliant data handling

**Analytics Features**:
- **Performance Trends**: Long-term progress tracking
- **Comparative Analysis**: Class and grade-level comparisons
- **Predictive Insights**: AI-powered performance predictions
- **Intervention Recommendations**: Automated suggestions for improvement

## 🌐 Multi-Language Support

### **Comprehensive Language Coverage**
Sahayak AI supports multiple languages to serve diverse educational communities across India and internationally:

#### **Primary Languages**
- **English** - Primary interface and content language
- **Hindi** - हिंदी - Indian national language, widely spoken across North India
- **Bengali** - বাংলা - Official language of West Bengal and Bangladesh
- **Bhojpuri** - भोजपुरी - Spoken in Eastern Uttar Pradesh, Bihar, and Jharkhand

#### **Regional Languages**
- **Tamil** - தமிழ் - Official language of Tamil Nadu
- **Telugu** - తెలుగు - Official language of Andhra Pradesh and Telangana
- **Kannada** - ಕನ್ನಡ - Official language of Karnataka

#### **International Languages**
- **Spanish** - Español - For international schools and Spanish-speaking communities
- **French** - Français - For international schools and French-speaking communities

### **Language Features**
- **Complete Interface Translation**: All UI elements, buttons, and navigation
- **Content Generation**: AI-powered content creation in all supported languages
- **Speech Recognition**: Voice input support for multiple languages
- **Text-to-Speech**: Audio output in native languages
- **Cultural Adaptation**: Region-specific examples and cultural references
- **Grade-Level Adaptation**: Language complexity matching educational standards

### **Technical Implementation**
- **JSON-based Localization**: Structured translation files for easy maintenance
- **Dynamic Language Switching**: Real-time language change without page reload
- **Context-Aware Translations**: Intelligent translation based on educational context
- **Fallback Mechanisms**: Graceful degradation to English for missing translations

## 🔧 Development Scripts

### **Core Development Commands**
```bash
# Development Servers
npm run dev              # Start Next.js development server (port 9002)
npm run genkit:dev       # Start Genkit AI development server
npm run genkit:watch     # Start Genkit with file watching for hot reload

# Production Build
npm run build            # Build application for production
npm run start            # Start production server
npm run export           # Export static files (if needed)

# Code Quality & Testing
npm run lint             # Run ESLint for code linting
npm run typecheck        # Run TypeScript type checking
npm run format           # Format code with Prettier
npm run lint:fix         # Fix auto-fixable linting issues

# AI Development
npx genkit run <flow>    # Run specific AI flow for testing
npx genkit start         # Start Genkit server manually
npx genkit build         # Build AI flows for production

# Database Operations
firebase emulators:start # Start Firebase emulators for local development
firebase deploy          # Deploy to Firebase
firebase firestore:export # Export Firestore data
```

### **Environment-Specific Commands**
```bash
# Development Environment
NODE_ENV=development npm run dev

# Production Environment
NODE_ENV=production npm run build
NODE_ENV=production npm run start

# Testing Environment
npm run test             # Run unit tests (if configured)
npm run test:e2e         # Run end-to-end tests (if configured)
```

### **Utility Commands**
```bash
# Package Management
npm audit               # Check for security vulnerabilities
npm update              # Update dependencies
npm outdated            # Check for outdated packages

# Development Tools
npx next info           # Display Next.js environment information
npx tsc --noEmit        # Type checking without emitting files
npx eslint --fix src/   # Fix linting issues in source directory
```

## 🚀 Deployment

### **Production Deployment Options**

#### **Vercel (Recommended)**
**Best for**: Next.js applications with automatic deployments

**Setup Process**:
1. **Connect Repository**: Link your GitHub repository to Vercel
2. **Configure Environment**: Set all environment variables in Vercel dashboard
3. **Build Settings**: 
   - Framework Preset: Next.js
   - Build Command: `npm run build`
   - Output Directory: `.next`
4. **Domain Configuration**: Set up custom domain (optional)
5. **Automatic Deployments**: Configure to deploy on push to main branch

**Environment Variables in Vercel**:
```env
# Copy all variables from .env.local
NEXT_PUBLIC_FIREBASE_API_KEY=your_key
GOOGLE_AI_API_KEY=your_key
COHERE_API_KEY=your_key
# ... all other environment variables
```

#### **Firebase Hosting**
**Best for**: Applications requiring Firebase integration

**Setup Process**:
1. **Install Firebase CLI**:
   ```bash
   npm install -g firebase-tools
   firebase login
   ```

2. **Initialize Firebase**:
   ```bash
   firebase init hosting
   ```

3. **Build and Deploy**:
   ```bash
   npm run build
   firebase deploy
   ```

4. **Configure firebase.json**:
   ```json
   {
     "hosting": {
       "public": "out",
       "ignore": ["firebase.json", "**/.*", "**/node_modules/**"],
       "rewrites": [
         {
           "source": "**",
           "destination": "/index.html"
         }
       ]
     }
   }
   ```

#### **Docker Deployment**
**Best for**: Containerized deployments

**Dockerfile**:
```dockerfile
FROM node:18-alpine

WORKDIR /app

COPY package*.json ./
RUN npm ci --only=production

COPY . .
RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]
```

**Docker Compose**:
```yaml
version: '3.8'
services:
  sahayakai:
    build: .
    ports:
      - "3000:3000"
    environment:
      - NODE_ENV=production
    env_file:
      - .env.production
```

### **Environment-Specific Configurations**

#### **Development Environment**
- **Database**: Firebase Emulator Suite
- **AI Services**: Development API keys with rate limiting
- **Logging**: Detailed console logging
- **Hot Reload**: Enabled for rapid development

#### **Staging Environment**
- **Database**: Separate Firebase project
- **AI Services**: Staging API keys
- **Monitoring**: Basic error tracking
- **Testing**: Automated testing pipeline

#### **Production Environment**
- **Database**: Production Firebase project
- **AI Services**: Production API keys with full quotas
- **Monitoring**: Comprehensive error tracking and analytics
- **Security**: HTTPS enforcement, CSP headers
- **Performance**: CDN integration, image optimization

### **Deployment Checklist**

#### **Pre-Deployment**
- [ ] All environment variables configured
- [ ] Firebase security rules updated
- [ ] API keys and quotas verified
- [ ] Database backup completed
- [ ] Performance testing completed
- [ ] Security audit passed

#### **Post-Deployment**
- [ ] Application accessible at production URL
- [ ] All features functioning correctly
- [ ] AI services responding properly
- [ ] Database connections established
- [ ] Monitoring and logging active
- [ ] SSL certificate valid
- [ ] Performance metrics within acceptable ranges

### **Monitoring & Maintenance**

#### **Performance Monitoring**
- **Vercel Analytics**: Built-in performance monitoring
- **Firebase Performance**: Real-time performance insights
- **Custom Metrics**: Application-specific monitoring

#### **Error Tracking**
- **Sentry Integration**: Error tracking and alerting
- **Firebase Crashlytics**: Mobile and web crash reporting
- **Custom Logging**: Application-specific error logging

#### **Health Checks**
- **API Endpoints**: Regular health check monitoring
- **Database Connectivity**: Connection pool monitoring
- **AI Service Status**: API availability monitoring

## 🤝 Contributing

### **Getting Started with Contribution**

We welcome contributions from educators, developers, and AI enthusiasts! Here's how you can contribute to Sahayak AI:

#### **Types of Contributions**
- **Feature Development**: New AI capabilities and educational tools
- **Bug Fixes**: Resolving issues and improving stability
- **Documentation**: Improving guides, tutorials, and API documentation
- **Localization**: Adding support for new languages
- **UI/UX Improvements**: Enhancing user experience and accessibility
- **Testing**: Writing tests and improving test coverage
- **Performance Optimization**: Improving speed and efficiency

#### **Development Setup**
1. **Fork the Repository**: Click "Fork" on GitHub
2. **Clone Your Fork**: 
   ```bash
   git clone https://github.com/your-username/sahayakai.git
   cd sahayakai
   ```
3. **Set Up Development Environment**: Follow the installation guide above
4. **Create Feature Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

#### **Development Guidelines**

##### **Code Standards**
- **TypeScript**: Use TypeScript for all new code
- **ESLint**: Follow the project's ESLint configuration
- **Prettier**: Use Prettier for code formatting
- **Naming Conventions**: Use descriptive names for variables and functions
- **Comments**: Add JSDoc comments for complex functions

##### **AI Flow Development**
- **Genkit Framework**: Use Genkit for all AI workflows
- **Type Safety**: Define input/output schemas for all flows
- **Error Handling**: Implement proper error handling and validation
- **Testing**: Test AI flows with sample data before committing

##### **UI Component Development**
- **Radix UI**: Use Radix UI primitives for accessibility
- **Tailwind CSS**: Follow the project's design system
- **Responsive Design**: Ensure components work on all screen sizes
- **Accessibility**: Follow WCAG guidelines for accessibility

#### **Commit Guidelines**
```bash
# Use conventional commit format
git commit -m "feat: add new quiz generation feature"
git commit -m "fix: resolve face recognition accuracy issue"
git commit -m "docs: update installation guide"
git commit -m "style: improve button component styling"
```

**Commit Types**:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

#### **Pull Request Process**
1. **Create Pull Request**: Submit PR with detailed description
2. **Code Review**: Address feedback from maintainers
3. **Testing**: Ensure all tests pass
4. **Documentation**: Update relevant documentation
5. **Merge**: PR will be merged after approval

#### **Issue Reporting**
When reporting issues, please include:
- **Environment**: OS, browser, Node.js version
- **Steps to Reproduce**: Detailed reproduction steps
- **Expected vs Actual Behavior**: Clear description
- **Screenshots/Logs**: Visual evidence if applicable
- **Error Messages**: Full error text and stack traces

### **Community Guidelines**

#### **Code of Conduct**
- **Respect**: Treat all contributors with respect
- **Inclusivity**: Welcome contributors from diverse backgrounds
- **Constructive Feedback**: Provide helpful, constructive feedback
- **Learning**: Support newcomers and help them learn

#### **Communication Channels**
- **GitHub Issues**: For bug reports and feature requests
- **GitHub Discussions**: For questions and community discussions
- **Pull Requests**: For code contributions and reviews

### **Recognition**
- **Contributors**: All contributors will be listed in the project
- **Special Thanks**: Significant contributions will be acknowledged
- **Badges**: Contributors will receive recognition badges

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### **License Terms**
- **Commercial Use**: Allowed for commercial purposes
- **Modification**: Allowed to modify and distribute
- **Distribution**: Allowed to distribute copies
- **Private Use**: Allowed for private use
- **Attribution**: Required to include license and copyright notice

### **Third-Party Licenses**
- **Google AI**: Subject to Google's API terms of service
- **Cohere AI**: Subject to Cohere's API terms of service
- **Firebase**: Subject to Google's Firebase terms of service
- **Open Source Libraries**: Various open source licenses

## 🙏 Acknowledgments

### **Core Technologies**
- **Google AI** - Advanced language models (Gemini) and video generation (Veo 3)
- **Cohere AI** - Enterprise-grade text generation and analysis capabilities
- **Firebase** - Comprehensive backend-as-a-service platform
- **Next.js** - React framework for production-grade applications
- **Genkit AI** - Google's AI framework for building intelligent applications

### **Open Source Community**
- **Radix UI** - Accessible, unstyled component primitives
- **Tailwind CSS** - Utility-first CSS framework
- **TypeScript** - Static type checking for JavaScript
- **React** - UI library for building user interfaces
- **Lucide React** - Beautiful, customizable icon library

### **Educational Partners**
- **Teachers and Educators** - For feedback and real-world testing
- **Students** - For user experience insights and feature requests
- **Schools and Institutions** - For pilot programs and adoption

### **Development Team**
- **AI/ML Engineers** - For implementing advanced AI capabilities
- **Frontend Developers** - For creating intuitive user interfaces
- **Backend Developers** - For building scalable infrastructure
- **UX/UI Designers** - For designing accessible and engaging experiences
- **DevOps Engineers** - For deployment and infrastructure management

## 📞 Support & Community

### **Getting Help**

#### **Documentation**
- **User Guide**: Comprehensive guide for teachers and administrators
- **API Documentation**: Technical documentation for developers
- **Tutorial Videos**: Step-by-step video tutorials
- **FAQ**: Frequently asked questions and answers

#### **Support Channels**
- **GitHub Issues**: For bug reports and feature requests
- **GitHub Discussions**: For questions and community discussions
- **Email Support**: For enterprise and institutional support
- **Video Calls**: For personalized training and onboarding

#### **Community Resources**
- **User Forum**: Community-driven support and discussions
- **Feature Requests**: Vote and suggest new features
- **Success Stories**: Share how Sahayak AI is being used
- **Best Practices**: Tips and tricks from experienced users

### **Enterprise Support**

#### **Institutional Deployment**
- **Custom Installation**: On-premise deployment options
- **Integration Services**: Custom integrations with existing systems
- **Training Programs**: Comprehensive training for staff and teachers
- **Ongoing Support**: Dedicated support team for institutions

#### **API Access**
- **Developer Documentation**: Complete API reference
- **SDK Libraries**: Client libraries for various programming languages
- **Webhook Support**: Real-time notifications and integrations
- **Rate Limiting**: Flexible rate limiting for different use cases

### **Contact Information**
- **General Inquiries**: info@sahayakai.com
- **Technical Support**: support@sahayakai.com
- **Enterprise Sales**: enterprise@sahayakai.com
- **Partnerships**: partnerships@sahayakai.com

---

<div align="center">
  <strong>Empowering Education with AI</strong><br/>
  <em>Making learning accessible, engaging, and effective for everyone.</em>
  
  <br/><br/>
  
  <p style="font-size: 0.9em; color: #666;">
    Built with ❤️ for the global education community<br/>
    Supporting teachers, empowering students, transforming education
  </p>
</div>
=======
# Shayak-Ai
>>>>>>> f1a97d243c28efe7ef166fbdb883914162da8407
