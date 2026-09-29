# Phase 12 — Final Launch & Maintenance

## Release status
The application build is prepared for production configuration. It is not publicly deployed from this workspace.

## Before launch
- Add the real Patrick Digital Hub logo and approved portfolio/video assets.
- Add verified social-media URLs only.
- Set production environment variables and strong unique secrets.
- Provision a persistent production database and upload storage.
- Configure transactional email for password reset and notifications.
- Configure HTTPS and secure cookies.
- Configure backups and test restoration.
- Configure malware scanning for uploaded files.
- Create the first production admin account securely.
- Run the Phase 10 test checklist in the actual hosting environment.

## Business details to verify
- Phone: 0746 576 897
- Email: mahugu2005@gmail.com
- Location: Nyeri, Kenya
- Business name: Patrick Digital Hub

## Launch acceptance test
1. Public homepage loads over HTTPS.
2. Portfolio filtering and previews work.
3. Contact/project request forms validate correctly.
4. Registration, login, logout and password reset work.
5. Client can only access their own projects.
6. Staff/admin authorization is enforced server-side.
7. Admin reporting uses real database values.
8. Upload restrictions and private storage work.
9. Rate limits and CSRF protections are active.
10. Backups complete and restoration has been tested.
11. No production secrets appear in source or client-side code.
12. Error logging and health monitoring are configured.

## Maintenance
- Apply security/dependency updates regularly.
- Review backups and restoration periodically.
- Monitor errors, storage and database health.
- Keep portfolio and service content current.
- Remove inactive accounts according to the site's retention policy.
- Review admin/staff permissions periodically.

## Deployment boundary
This package is a release candidate, not a claim of public deployment. Domain, hosting, DNS, production credentials, email provider, persistent storage and monitoring must be configured in the target environment.
