# WebRTCPeer: Convenience wrapper for the WebRTC API. #

You can require this module into a Node project or directly link to the
WebRTCPeer.js file in the browser.  Most of the time, WebRTC communication is
between browsers, and a node.js server is only used to coordinate
communication.  In that case, you don't need to use the wrtc module that is
ostensibly a dependency.  That module is an implementation of the WebRTC API
for node.js.  If you're only using browsers, then each browser has its own
WebRTC implementation.

Detailed documentation on how to use this module is in the comments.  I should
probably run jsdoc or something.
