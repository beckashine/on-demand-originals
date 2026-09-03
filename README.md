# Custom E-Commerce Website

## Client Website & Technical Implementation

**Live Demo Admin Login:** [on-demand-originals.netlify.app](https://on-demand-originals.netlify.app/admin.login)<br>
        **Email** - demo@login.com | **PW** demo123

## The Project

On-Demand Originals is a client e-commerce website built around the client's goals, requirements, and desired user experience.

I started by understanding what the client needed the site to accomplish and the design they had in mind. I then translated those requirements into the design, functionality, and implementation plan.

## My Process

I approached the project as an implementation from requirements through delivery:

**Understand → Plan → Design → Implement → Test → Validate → Deliver**

I used AI-assisted development to help turn the project plan and design requirements into a working application.

My responsibility was defining the requirements, directing the implementation, making decisions about how the different pieces should work together, testing the result, troubleshooting issues, and validating the finished experience.

## Integrations

The application connects several services to support the client's business requirements:

| Service      | Purpose                               |
| ------------ | ------------------------------------- |
| **PayPal**   | Payment processing                    |
| **Brevo**    | Newsletter delivery                   |
| **Supabase** | Application database and data storage |

### Deployment

**Netlify** is used for application hosting and deployment.

These services work together to provide the functionality needed for the client's e-commerce workflow.

## Security

Security was considered throughout the implementation.

During development and testing, API keys and other sensitive configuration values were kept out of the application code and stored in a local `.env.local` file. This allowed credentials to be securely provided to the application during testing without exposing them directly in the source code.

I also considered what information each connected service should have access to and how data moves between the application and those services.

## Challenges & Troubleshooting

During development, I worked through issues involving application behavior, integrations, and implementation details.

I used testing, documentation, error messages, research, and AI-assisted troubleshooting to identify problems, make corrections, and verify the results.

This process allowed me to understand how the different components interact and work through technical problems when the initial implementation does not behave as expected.

## What This Project Demonstrates

This project demonstrates my ability to:

* Understand client requirements
* Translate requirements into an implementation plan
* Design a solution around those requirements
* Coordinate multiple application components
* Connect services through APIs
* Consider security throughout implementation
* Troubleshoot technical issues
* Use AI-assisted development to execute a project
* Test and validate the finished solution
* Deliver a working client implementation

---

### Implementation Flow

```text
Client Requirements
        ↓
Project Plan
        ↓
Design & User Experience
        ↓
Application Implementation
        ↓
 ┌──────┼────────┐
 ↓      ↓        ↓
PayPal Supabase  Brevo
 ↓      ↓        ↓
 └──────┼────────┘
        ↓
Testing & Validation
        ↓
Production Deployment
        ↓
   Client Delivery
```
