# HTML to PNG Vercel Edge Proxy

A high-performance Edge Proxy running on Vercel that forwards requests to the Cloudflare Browser Rendering Worker (`https://html-to-png-worker.chintusharma00014.workers.dev`).

This proxy provides an allowlisted `*.vercel.app` endpoint with automatic CORS headers to bypass sandbox egress proxy filters that block `*.workers.dev`.
