# GSX2026
This is the pointer README.md for GSX 2026 presentation "Empowering Physical Security Systems with AI: Leveraging LLMs and RAG for Seamless API Integration" to be given at GSX 2026 in Atlanta, GA.

Here you will find sample code for the three LLM/RAG/MCP/API examples that were part of the presentation, the mcp-chat terminal client, and videos of some of the included demos.   The various repos are shared here:
* https://github.com/cdp/GSX2026-axis-camera-mcp
* https://github.com/cdp/GSX2026-milestone_xprotect
* https://github.com/cdp/GSX2026-Amag.Symmetry
* https://github.com/cdp/GSX2026-mcp-chat
* https://github.com/cdp/GSX2026-presentation-videos

20260818

Comment was made during the presentation related to Milestone XProect that we could not get vlc to view live video.  That statement was true when using VLC.  However, if I wuold have thought about the issue a little more, a WebRTC stream may have been possible from the server.    We could have tried:
* Eyevinn WebRTC Player: A pure web-based open-source player component compatible with any WebRTC media server implementing WHEP.
* go2rtc: An ultimate camera streaming application that supports WebRTC, WHEP, and various smart home/IP camera feeds with a built-in viewer interface.

The issue we hit was related to calling the stream and when tried to redirect to the XProtect web interface, we hit that roadblock.     That may have been a non-issue with one of the above tools.

20260916
