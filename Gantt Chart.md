```mermaid
gantt
    title Global HealthCure Project Timeline
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d

    section February: Research & Planning
    Research & Competitor Analysis     :done, a1, 2024-02-01, 7d
    Requirement Gathering              :done, a2, 2024-02-08, 7d
    Wireframing & UI Prototyping       :done, a3, 2024-02-15, 7d
    Tech Stack Upskilling & Setup      :done, a4, 2024-02-22, 7d

    section March 1 - March 17: UI Development & Backend Setup
    Flutter Project Setup              :done, b1, 2024-03-01, 5d
    Firebase Integration (Auth, DB)    :done, b2, 2024-03-06, 5d
    UI Screens Development (Login, Home, Profile) :done, b3, 2024-03-11, 6d
    AI & OCR UI Design                 :done, b4, 2024-03-15, 3d

    section March 12 - March 20: Core Backend Development
    Firestore Schema Design            :active, c1, 2024-03-12, 2d
    Authentication & Role-based Access :active, c2, 2024-03-14, 2d
    Consultation Booking System        :active, c3, 2024-03-16, 2d
    AI & OCR API Integration           :active, c4, 2024-03-18, 2d

    section March 21 - March 24: Payment & Admin Panel
    Payment Gateway Integration        :c5, 2024-03-21, 2d
    Admin Panel Development            :c6, 2024-03-23, 2d
    Doctor Validation Flow             :c7, 2024-03-24, 1d

    section March 25 - March 29: Testing & Optimization
    Unit Testing (User & Doctor Flow)  :d1, 2024-03-25, 2d
    Integration Testing                 :d2, 2024-03-27, 2d
    Security & Performance Review       :d3, 2024-03-29, 1d

    section March 30 - March 31: Deployment & Review
    Final UI/UX Enhancements           :e1, 2024-03-30, 1d
    Deployment & Documentation         :e2, 2024-03-31, 1d
