# Call The Mind Curator Studio

Public client call page for The Mind Curator Studio.

Open the page, enter the studio call code (mcs-desk-...) or open the link with ?code=mcs-desk-... in it, tap Start call and talk. The studio AI receptionist answers from the private Studio Desk; replies are spoken aloud on this page.

No Desk access, no keys, no records on this page.

## Studio receiver (owner only)

`receiver.html` is the receiving side: open it on the studio computer, press
"Start receiving calls", and keep the tab open. Simple logic — one PeerJS
peer with the call code (default `mcs-desk-qgb10typ`), no retries or
reconnect loops. The AI receptionist auto-answers: Groq key or FreeLLMAPI
address/key are entered once on that page and stored only in that browser.
