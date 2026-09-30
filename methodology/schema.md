# Schema (minimal)

## Case
- `case_id` (PL-YYYY-NNNN)
- `title`, `disclosure_date`, `status`, `mechanism_family`
- `INFO.md` narrative + public URLs only

## Source
- `source_id`, `url`, `publisher`, `date`, `case_ids`

## Indicator
- `indicator_id`, `type` (tool|pattern|product|repo_path|gap)
- `value`, `status`, `availability` optional

## Relationship
- `from_id`, `to_id`, `relation`, `review_state`

## Timeline row
- `date`, `case_id`, `event`, `status`, `source_ids`
