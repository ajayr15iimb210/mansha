# Mansha - Navigate Your Perfect Career Path

<div align="center">
  <h3>Free Online Career Counseling Platform for Indian School Students</h3>
  <p>Comprehensive career guidance for students in grades 7-12</p>
  
  [![React](https://img.shields.io/badge/React-18-blue.svg)](https://reactjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5-blue.svg)](https://www.typescriptlang.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.0-38B2AC.svg)](https://tailwindcss.com/)
  [![Supabase](https://img.shields.io/badge/Supabase-Backend-green.svg)](https://supabase.com/)
  [![OpenAI](https://img.shields.io/badge/OpenAI-AI_Powered-orange.svg)](https://openai.com/)
</div>

## 🎯 About Mansha

Mansha is a comprehensive, free online career counseling platform specifically designed for Indian school students in grades 7-12. Our mission is to bridge the gap between students' aspirations and informed career decisions by providing data-driven insights, AI-powered recommendations, and extensive career information.

### 🌟 Key Highlights

- **115+ Career Profiles** - Balanced mix of government and private sector opportunities
- **AI-Powered Assessments** - Personalized career recommendations using OpenAI
- **Mobile-First Design** - Optimized for smartphones with 18px minimum font size
- **Comprehensive Database** - 6GB+ of career data with 894,671+ records
- **Multi-Stream Coverage** - Science, Commerce, Arts, and Vocational streams
- **Real-Time Analytics** - Track user engagement and popular career paths

## 🚀 Features

### Core Functionality
- **Career Explorer** - Browse and filter 115+ detailed career profiles
- **AI Career Assessment** - Intelligent questionnaire for personalized recommendations
- **Career Comparison** - Side-by-side comparison of different career paths
- **My Journey** - Personal profile and career tracking system
- **Career Gyan** - Educational content and career insights
- **Community Platform** - Q&A system with AI-powered responses

### Advanced Features
- **PDF Export** - Download comprehensive career reports
- **User Authentication** - Secure login with profile management
- **Admin Dashboard** - Complete content management system
- **Database Management** - Advanced cleanup and optimization tools
- **Real-time Chat** - AI-powered career counseling chatbot
- **Mobile Optimization** - Full responsive design with bottom navigation

### Technical Features
- **Performance Optimized** - Lazy loading and efficient data management
- **SEO Friendly** - Proper meta tags and structured data
- **Analytics Integration** - Comprehensive user behavior tracking
- **Error Handling** - Robust error boundaries and fallbacks
- **Progressive Enhancement** - Works on all devices and browsers

## 🛠️ Technology Stack

### Frontend
- **React 18** - Modern React with hooks and functional components
- **TypeScript** - Type-safe development
- **Tailwind CSS v4** - Utility-first CSS framework with custom design system
- **Lucide React** - Beautiful icons
- **Recharts** - Data visualization and charts
- **Motion (Framer Motion)** - Smooth animations

### Backend
- **Supabase** - Backend-as-a-Service
- **Supabase Edge Functions** - Serverless API endpoints
- **Hono** - Fast web framework for edge functions
- **PostgreSQL** - Robust database with key-value store

### AI & External Services
- **OpenAI API** - AI-powered career recommendations
- **Supabase Auth** - User authentication and authorization
- **Supabase Storage** - File and media storage

### Development Tools
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Git** - Version control

## 📁 Project Structure

```
├── components/                 # React components
│   ├── ui/                    # Reusable UI components (shadcn/ui)
│   ├── sections/              # Homepage sections
│   └── figma/                 # Figma integration components
├── contexts/                  # React contexts
├── hooks/                     # Custom React hooks
├── utils/                     # Utility functions
├── data/                      # Static data and constants
├── styles/                    # Global CSS and Tailwind config
├── supabase/functions/server/ # Backend API endpoints
└── App.tsx                    # Main application component
```

### Key Directories

- **`/components`** - All React components organized by functionality
- **`/hooks`** - Custom hooks for data fetching, navigation, and state management
- **`/supabase/functions/server`** - Backend API endpoints and business logic
- **`/utils`** - Helper functions for analytics, API calls, and data processing
- **`/contexts`** - React context providers for global state

## 🚦 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn
- Supabase account
- OpenAI API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mansha.git
   cd mansha
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env.local` file in the root directory:
   ```env
   SUPABASE_URL=your_supabase_project_url
   SUPABASE_ANON_KEY=your_supabase_anon_key
   SUPABASE_SERVICE_ROLE_KEY=your_supabase_service_role_key
   OPENAI_API_KEY=your_openai_api_key
   ```

4. **Supabase Setup**
   - Create a new Supabase project
   - Run the database migrations (if any)
   - Set up the `kv_store_d51afe13` table for data storage
   - Configure authentication providers if needed

5. **Deploy Edge Functions**
   ```bash
   npx supabase functions deploy
   ```

6. **Start Development Server**
   ```bash
   npm run dev
   ```

The application will be available at `http://localhost:3000`

### Admin Access

To access the admin panel:
1. Navigate to `/?admin=true`
2. Sign in with admin credentials
3. Access comprehensive dashboard for content management

## 📱 Mobile-First Design

Mansha is built with a mobile-first approach:

- **18px minimum font size** on mobile devices for accessibility
- **Touch-friendly interfaces** with 44px minimum touch targets
- **Bottom navigation** for easy thumb navigation
- **Responsive layouts** that work seamlessly across all screen sizes
- **Performance optimized** for mobile networks

## 🎨 Design System

### Typography Scale
- Mobile: 18px minimum for all text
- Desktop: Allows smaller text (14px+) for better design flexibility
- Custom CSS variables for consistent spacing and sizing

### Color Palette
- Primary: `#030213` (Dark navy)
- Secondary: Light grays and blues
- Theme Blue: `#2563eb`
- Success, Warning, and Error states included

### Components
- Built on shadcn/ui component library
- Custom components for career-specific functionality
- Consistent spacing and interaction patterns

## 🔧 Configuration

### Database Management
The platform includes sophisticated database management tools:

- **Cleanup System** - Remove unnecessary data and optimize performance
- **Batch Operations** - Efficient bulk data operations
- **Monitoring** - Track database size and performance metrics
- **Backup & Restore** - Data safety and recovery tools

### Analytics
Comprehensive analytics tracking:
- Page visits and user flows
- Career profile interactions
- Search patterns and popular careers
- Assessment completion rates
- Admin actions and data changes

## 🤝 Contributing

We welcome contributions to make Mansha better for students across India!

### Development Guidelines

1. **Code Style**
   - Follow TypeScript best practices
   - Use functional components with hooks
   - Follow the existing file structure
   - Write descriptive commit messages

2. **Component Development**
   - Create reusable components in `/components`
   - Use Tailwind CSS for styling
   - Ensure mobile-first responsiveness
   - Include proper TypeScript types

3. **Backend Development**
   - Add new endpoints in `/supabase/functions/server`
   - Use the existing KV store pattern
   - Include proper error handling
   - Document API endpoints

### Submitting Changes

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly on mobile and desktop
5. Submit a pull request with detailed description

## 📊 Data & Privacy

### Data Handling
- User data is stored securely in Supabase
- No personal information is required for basic usage
- Optional user profiles for enhanced experience
- GDPR-compliant data practices

### Career Data
- 115+ verified career profiles
- Regular updates to salary and requirement information
- Sourced from reliable industry data
- Covers all major education streams in India

## 🚀 Deployment

The application can be deployed on various platforms:

### Recommended: Vercel
```bash
npm install -g vercel
vercel --prod
```

### Alternative: Netlify
```bash
npm run build
# Upload dist folder to Netlify
```

### Environment Variables
Ensure all environment variables are configured in your deployment platform.

## 📈 Roadmap

### Upcoming Features
- [ ] Regional language support (Hindi, Tamil, Bengali)
- [ ] College admission guidance
- [ ] Scholarship database integration
- [ ] Video content and virtual career fairs
- [ ] Parent dashboard and involvement tools
- [ ] Advanced analytics and reporting

### Long-term Vision
- Expand to cover undergraduate and postgraduate career paths
- Integration with educational institutions
- Employer partnerships for direct opportunities
- AI-powered interview preparation tools

## 🐛 Known Issues

- Large database size (6GB+) may require periodic cleanup
- Mobile chat performance optimization ongoing
- Some edge cases in career comparison feature

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **shadcn/ui** for the excellent component library
- **Supabase** for reliable backend infrastructure
- **OpenAI** for AI-powered recommendations
- **Tailwind CSS** for the utility-first CSS framework
- **Lucide** for beautiful icons
- All the educators and career counselors who provided insights

## 📞 Support

For support, questions, or suggestions:

- **Issues**: Use GitHub Issues for bug reports and feature requests
- **Discussions**: Join GitHub Discussions for community support
- **Email**: Contact the maintainers for critical issues

## 🌟 Star History

If you find Mansha helpful, please consider giving it a star on GitHub! Your support helps us reach more students who need career guidance.

---

<div align="center">
  <p><strong>Made with ❤️ for Indian students</strong></p>
  <p>Empowering the next generation to make informed career decisions</p>
</div>
