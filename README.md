<h1>Personal Finance Manager</h1>
    <p>
        A secure and user-friendly web application for managing personal finances, enabling users to track expenses, gains, financial goals, and more.
    </p>
    <h2>Main Features</h2>
    <ul>
        <li><strong>User Management:</strong> Register, login, update details, and change passwords securely using JWT-based authentication.</li>
        <li><strong>Balance Management:</strong> Track balances across various modes such as cash, bank accounts, and digital wallets.</li>
        <li><strong>Expense and Gain Tracking:</strong> Log and categorize current expenses or gains and view transaction history with filters.</li>
        <li><strong>Future Planning:</strong> Create and track upcoming expenses or gains with reminders.</li>
        <li><strong>Financial Goals:</strong> Set and monitor financial goals with progress tracking.</li>
        <li><strong>Monthly Spending Threshold:</strong> Set a monthly spending limit, track progress, and receive alerts when limits are approached or exceeded. Automated calculations at month-end using Spring Scheduler and cron expressions.</li>
        <li><strong>Financial Notes:</strong> Create, update, and manage financial notes for personal reference.</li>
        <li><strong>Tagging and Querying:</strong> Assign tags to transactions or notes for better organization and quick retrieval.</li>
    </ul>
    <h2>Technology Stack</h2>
    <h3>Backend</h3>
    <ul>
        <li><strong>Java 17:</strong> Core programming language.</li>
        <li><strong>Spring Boot:</strong> Framework for backend services and RESTful APIs.</li>
        <li><strong>Spring Security (JWT):</strong> Authentication and authorization.</li>
        <li><strong>Spring Data JPA/Hibernate:</strong> ORM for managing database interactions.</li>
        <li><strong>PostgreSQL:</strong> Structured database for transactions and financial data.</li>
        <li><strong>MongoDB:</strong> Unstructured database for notes and logs.</li>
        <li><strong>Spring Scheduler:</strong> Automate monthly calculations and threshold tracking.</li>
    </ul>
    <h3>Frontend</h3>
    <ul>
        <li><strong>Angular:</strong> Frontend framework for building dynamic and responsive UI.</li>
        <li><strong>TypeScript:</strong> Language for structured and maintainable frontend code.</li>
        <li><strong>SCSS:</strong> For styling and consistent UI design.</li>
        <li><strong>Figma:</strong> Tool for designing user interfaces and workflows.</li>
    </ul>
