```mermaid
gantt
    title Global HealthCure Project Timeline
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d
    
    %% February - Research & Planning
    section February: Research & Planning
    Research & Competitor Analysis     :done,   crit, a1, 2024-02-01, 7d
    Requirement Gathering              :done,   crit, a2, 2024-02-08, 7d
    Wireframing & UI Prototyping       :done,   crit, a3, 2024-02-15, 7d
    Tech Stack Upskilling & Setup      :done,   crit, a4, 2024-02-22, 7d

    %% March 1 - March 17: UI Development & Backend Setup
    section March 1-17: UI Development & Backend Setup
    Flutter Project Setup              :done,   active, b1, 2024-03-01, 5d
    Firebase Integration (Auth, DB)    :done,   active, b2, 2024-03-06, 5d
    UI Screens Development (Login, Home, Profile) :done, active, b3, 2024-03-11, 6d
    AI & OCR UI Design                 :done,   active, b4, 2024-03-15, 3d

    %% March 12 - March 20: Core Backend Development
    section March 12-20: Core Backend Development
    Firestore Schema Design            :active, c1, 2024-03-12, 2d
    Authentication & Role-based Access :active, c2, 2024-03-14, 2d
    Consultation Booking System        :active, c3, 2024-03-16, 2d
    AI & OCR API Integration           :active, c4, 2024-03-18, 2d

    %% March 21 - March 24: Payment & Admin Panel
    section March 21-24: Payment & Admin Panel
    Payment Gateway Integration        :crit,   c5, 2024-03-21, 2d
    Admin Panel Development            :crit,   c6, 2024-03-23, 2d
    Doctor Validation Flow             :crit,   c7, 2024-03-24, 1d

    %% March 25 - March 29: Testing & Optimization
    section March 25-29: Testing & Optimization
    Unit Testing (User & Doctor Flow)  :d1, 2024-03-25, 2d
    Integration Testing                 :d2, 2024-03-27, 2d
    Security & Performance Review       :crit, d3, 2024-03-29, 1d

    %% March 30 - March 31: Deployment & Review
    section March 30-31: Deployment & Review
    Final UI/UX Enhancements           :crit, e1, 2024-03-30, 1d
    Deployment & Documentation         :crit, e2, 2024-03-31, 1d
