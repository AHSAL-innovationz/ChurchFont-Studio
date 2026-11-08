Continue building ChurchFont Studio from the existing v0.2.0 engineering prototype.

Preserve the current application, existing functionality, document model, multi-page editing, image uploads, autosave, project library, JSON import/export, and print workflow.

Move backend development to a dedicated Cloudflare architecture:

1. Create a separate ChurchFont Cloudflare Worker API.
2. Use a dedicated Cloudflare D1 database.
3. Plan isolated asset storage.
4. Preserve owner-level access controls and data isolation.
5. Keep the architecture compatible with future Supabase migration.

Do not modify, pause, delete, or reuse any existing AHSAL Innovations application infrastructure.

Complete the engineering foundation first. Test existing features and new backend functionality. Then proceed to the full ChurchFont Studio visual design.

Prioritize free-tier resources, source ownership, security, responsive functionality, and maintainable code. Clearly identify anything requiring paid services or manual authorization before proceeding.