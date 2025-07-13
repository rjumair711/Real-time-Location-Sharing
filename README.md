# 📍 Real-Time Location Sharing (SignalR + Next.js)

A real-time location sharing web app using **Next.js**, **SignalR**, and **Leaflet**. This project demonstrates communication between two users:

- **User A (Sender):** Sends live GPS coordinates (simulated or real)
- **User B (Receiver):** Listens for updates and displays the location on a dynamic map

---

## 🚀 Features

- Real-time WebSocket connection with [SignalR](https://learn.microsoft.com/en-us/aspnet/core/signalr/introduction)
- Live map visualization with [Leaflet](https://leafletjs.com/)
- Modular `useSignalR` React hook
- Separate UI for sender and receiver
- Built with **Next.js App Router** and React 19

---

## 📦 Tech Stack

- ✅ Next.js 15 (App Router)
- ✅ React 19
- ✅ SignalR (via `@microsoft/signalr`)
- ✅ React-Leaflet & Leaflet
- ✅ TypeScript

---

## 🔧 Installation

```bash
git clone https://github.com/your-username/real-time-location-sharing.git
cd real-time-location-sharing

# Install dependencies
npm install

# Run development server
npm run dev
