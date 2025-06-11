# Vacation Tracking System

## Domain

In today's workplaces, employees often work on
several projects and may report to more than
one manager. Because of this, it's harder to keep
track of vacation time in informal ways.
Managers don’t always know when people are off,
and the old approval process is slow and takes
too much effort from HR.

## Vision

To provide individual employees with the
capability to manage their own vacation time, sick leave, and personal time off,
without having to be an expert in company policy or the local facility’s leave
policies.

## Functional

- Implements a flexible, rules-based system for validating and verifying leave requests
- Enables optional manager approval for leave requests
- Lets employees view the status of their requests and track their remaining leave balances
- Provides access to requests from the previous calendar year and allows future requests up to 18 months ahead
- Sends email notifications for manager approvals and status updates
- Maintains activity logs for all transactions
- Allows HR and system administrators to override rule-restricted actions, with override logging
- Lets managers award personal leave time directly, within system-defined limits
- Offers a web service interface for internal systems to query an employee’s vacation request summary
- Integrates with legacy HR systems to retrieve employee information and updates

## Non-Functional

- Security
- Ease of use
- Performance
- Scalability
- Auditability

## Constraints

- Uses existing hardware and middleware.
- Must be implemented as an extension to the existing intranet portal system.
- System-Set Limits on Manager Awarded Time.
- Must use the portal’s single sign-on (SSO) mechanism for all authentication.

## Actors
- Clerk
- Employee
- Manager
- System Admin


