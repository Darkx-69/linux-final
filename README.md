#  Live Crypto Streamer (Containerized with Podman)

This project demonstrates core concepts of Linux and Container Technologies by deploying a simple, responsive web application as a container image using **Podman** on a RHEL-based environment.

-----

## 1\. Project Goal

To create a "financial streamer" dashboard that displays live-updating cryptocurrency prices, packaged as a containerized web service.

## 2\. Technologies Used

* **Operating System:** RHEL-compatible Linux distribution
* **Container Runtime:** **Podman** (daemonless container engine, preferred on RHEL)
* **Web Server:** Nginx (used inside the container to serve the HTML)
* **Frontend:** HTML5, **Tailwind CSS** (for responsiveness), and JavaScript (for price simulation).

## 3\. Application Details

The application is a single-page, dark-mode dashboard (`index.html`) featuring:

* Real-time simulated price updates (since external API calls are restricted in some container environments).
* Fully responsive design using Tailwind CSS for optimal viewing on mobile, tablet, and desktop devices.
* Data is updated every 2 seconds.

----- n 

Cointainer image link:-
 https://quay.io/repository/umaaditya7809/crypto-streamer