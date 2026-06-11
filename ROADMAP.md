# STRYVR Public Roadmap

This roadmap is public-facing and intentionally excludes private implementation details.

## Phase 1: Product Foundation

Status: Complete

- Core app navigation
- Dashboard
- Workouts
- Recovery
- Nutrition
- Coach
- Progress
- Settings

## Phase 2: Workout Execution

Status: Complete / validating

- Start workout from plan
- Track active session time
- Pause, resume, and finish workout
- Log sets and completed work
- Preserve active workout across navigation
- Store workout history

## Phase 3: Wearable Recovery Intelligence

Status: In validation

- Polar AccessLink connection
- Biometric sync state handling
- Recovery score hydration
- HRV, sleep, resting heart rate, activity, and training-load support where available
- Active-session heart-rate telemetry

Next:

- Real-device sync validation
- Clear consent and permission messaging
- Better stale-data handling
- More complete biometric summaries

## Phase 4: Movement Intelligence

Status: In validation

- Camera-based pose tracking
- Movement assessment modes
- Squat assessment
- Balance assessment
- Jump readiness
- Mobility scan
- Coordination scan

Next:

- Improve assessment confidence gates
- Require enough valid movement data before scoring
- Expand physical-device test coverage
- Improve report clarity and reproducibility

## Phase 5: Form Check

Status: In progress

- Uploaded video analysis
- Exercise-specific rule profiles
- Detection-confirmation flow
- Camera-angle guidance
- Good form reference architecture

Next:

- Add real reference videos
- Add pose landmark analysis for uploaded videos
- Add exercise-specific joint-angle rules
- Add confidence scoring for visibility, angle, rep count, and movement quality

## Phase 6: AI Coach

Status: Active

- Generate training plans
- Save plans to workouts
- Provide coaching guidance

Next:

- Improve plan personalization with recovery and training context
- Add stronger review before saving generated plans
- Improve consistency between Coach, Workouts, and Dashboard

## Phase 7: Public Beta Readiness

Status: Upcoming

- Full mobile QA
- Published deployment smoke tests
- Wearable integration validation
- Privacy and consent review
- Error-state polish
- Performance pass
- Public onboarding flow

## Phase 8: Commercial Launch Preparation

Status: Future

- Subscription strategy
- Legal/privacy review
- Support workflows
- Production analytics
- Public marketing site
- App store readiness if native mobile launches
