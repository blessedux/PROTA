# PROTA Development TODO

## Vision

PROTA is the AI-powered companion app for goal tracking, accountability, and meal optimization. This roadmap outlines our journey from POC to the world's biggest restaurant, making lives more efficient through personalized AI guidance and meal delivery.

## Development Phases

### Phase 1 — Core UI & Explanation Flow

**Status**: Not Started  
**Priority**: High  
**Timeline**: 1-2 weeks

#### Tasks:

- [ ] Create simple landing page explaining PROTA
  - [ ] What PROTA is
  - [ ] Key features (task tracker, AI companion, meal planning, delivery option)
  - [ ] Visual walkthrough or animation of daily user flow
- [ ] Build onboarding flow
  - [ ] User sets main goals (Health, Career, Relationships, Spirituality, Creative)
  - [ ] Pick daily habit suggestions
  - [ ] Choose plan. meal planning is for free. delivery of food is the business.
- [ ] Design and implement core UI components
  - [ ] Navigation system
  - [ ] Goal setting interface
  - [ ] Basic task management UI

### Phase 2 — AI Companion Integration

**Status**: Not Started  
**Priority**: High  
**Timeline**: 2-3 weeks

#### Tasks:

- [ ] Integrate Vercel SDK for AI interface layer
- [ ] Research fast open-source LLMs on Hugging Face
- [ ] Test small models optimized for real-time goal tracking
- [ ] Fine-tune model with specific traits:
  - [ ] No irrelevant topics (no chit-chat, no politics)
  - [ ] Focus only on goals, mental clarity, and organization
  - [ ] Conversational tone: supportive, helpful, calm
- [ ] Create structured prompt system:
  - [ ] Morning: "What's your focus today?"
  - [ ] Midday: "How's it going?"
  - [ ] Evening: "Let's reflect on today."
- [ ] Implement AI conversation interface
- [ ] Add voice mode for hands-free check-ins
- [ ] Add notification system
- [ ] Task Slashing UI (Slash inspo)
- [ ] Visualization Room (Goal list and duration based navigation in viusally immersive timeline)

### Phase 3 — Meal System

**Status**: Not Started  
**Priority**: Medium  
**Timeline**: 2-3 weeks

#### Tasks:

- [ ] Build clean UI for meal management:
  - [ ] Meal recipes and nutritional info
  - [ ] Meal images
  - [ ] Meal Carrousel
  - [ ] daily or weekly meal plan UI
  - [ ] Simple Feedback on each meal preference
  - [ ] Caloric tracker of consumed food
- [ ] Connect to delivery system:
  - [ ] Integrate with delivery logistics (Dark kitchen + Daily Delivery)
  - [ ] Users opt-in to meal delivery by clicking on your planned meal for the day, or showing list of ingredients in order to cook yourself and check nutritional info.
  - [ ] Payment & plan selection system
- [ ] Implement meal preference learning
- [ ] Create recipe database and meal suggestions

### Phase 4 — Smart Assistant Memory & Flow

**Status**: Not Started  
**Priority**: Medium  
**Timeline**: 2-3 weeks

#### Tasks:

- [ ] Enable AI memory system:
  - [ ] Remember user goals and tasks
  - [ ] Suggest baby steps daily based on goal history
  - [ ] Give nudges based on streaks and feedback patterns
- [ ] Implement Power List system (Pomodoro-style daily focus)
- [ ] Build habit tracker with streak monitoring
- [ ] Create notification-based accountability system
- [ ] Develop progress visualization and reports

### Phase 5 — PWA & Mobile Optimization

**Status**: Not Started  
**Priority**: Medium  
**Timeline**: 1-2 weeks

#### Tasks:

- [ ] Convert to Progressive Web App (PWA)
- [ ] Optimize for mobile experience
- [ ] Implement offline functionality
- [ ] Add push notifications
- [ ] Ensure fast loading times

### 💰 Phase 6 — Monetization & Fundraising

**Status**: Not Started  
**Priority**: Low  
**Timeline**: 2-4 weeks

#### Tasks:

- [ ] Implement subscription system
- [ ] Create pricing tiers
- [ ] Build investor pitch deck
- [ ] Prepare fundraising materials
- [ ] Launch beta testing program

### Phase 7 — Food Preparation & Delivery

**Status**: Not Started  
**Priority**: Low  
**Timeline**: 3-6 months

#### Tasks:

- [ ] Partner with local kitchens
- [ ] Develop packaging system
- [ ] Create recipe standardization
- [ ] Build delivery logistics
- [ ] Implement quality control
- [ ] Scale delivery operations

## Tech Stack & Priorities

### Core Technologies:

- **Frontend**: Next.js + Tailwind CSS
- **Backend**: Node.js (Express) or Serverless (Vercel functions)
- **Database**: Supabase / PostgreSQL
- **AI**: Open-source LLM (DeepSeek / Ollama) with custom fine-tuning
- **TTS**: ElevenLabs multilingual emotional speech
- **Notifications**: Push + In-app via Firebase or OneSignal
- **Meal Delivery**: Third-party logistics API integrations

### Technical Priorities:

- [ ] Setup codebase with modular structure
- [ ] AI backends tested and abstracted for swapping models
- [ ] Local storage fallback if no account
- [ ] Fast mobile experience (PWA optional)
- [ ] Implement proper error handling
- [ ] Add comprehensive testing
- [ ] Set up CI/CD pipeline

## Immediate Next Steps

1. **Start with Phase 1**: Build the walkthrough page that shows how PROTA works in 1 minute
2. **Test UI + flow immediately**: Get user feedback on core experience
3. **Plug in the AI**: Integrate basic AI functionality
4. **Iterate fast**: Use feedback to improve rapidly

## Project Management

### Development Principles:

- Move fast and test UI + flow immediately
- Use what you have, start where you are, do what you can
- Focus on user experience and value delivery
- Build modular components for easy scaling

### Success Metrics:

- User engagement with AI companion
- Task completion rates
- Meal plan adherence
- User retention and satisfaction
- Revenue from meal delivery subscriptions
