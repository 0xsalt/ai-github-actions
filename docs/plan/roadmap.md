knowledge/
├─ README.md
├─ assistant/
│  ├─ defaults.yaml              # GPT boot config it fetches at conversation start
│  ├─ default-note.md            # The note to show/load first
│  ├─ templates/                 # commit msg + note templates
│  └─ rules.md                   # writing rules, style guide
├─ para/
│  ├─ projects/                  # active projects
│  ├─ areas/                     # ongoing responsibilities
│  ├─ resources/                 # reference material
│  └─ archives/                  # completed/old
├─ inbox/                        # stream-of-consciousness dropbox
├─ logs/
│  ├─ events.jsonl               # append-only log entries
│  └─ sync/                      # action run logs / snapshots
└─ index/
   ├─ registry.json              # machine index of notes (IDs, paths, tags)
   └─ tags.json                  # reverse index of tag -> file[]

