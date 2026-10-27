# PostMedia

**Public.** Images that post pipelines hand to Buffer by URL. Buffer has no upload API, so each
accepted post's image is committed here and Buffer fetches it from `raw.githubusercontent.com`.

- One top-level folder per pipeline: `mckenzy/` for McKenzy Cresswell's LinkedIn posts.
- Only images for posts that have been accepted go here — never drafts, briefs or review notes.
- File names carry a content hash, so a URL never changes underneath a draft. Files are not
  deleted after a post goes live.

Written by the scheduled review-sync tasks; see `MotorsportMarketing/mckenzy` `tasks/review-sync.md` step 3.6a.
