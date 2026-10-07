# ARP Interactive Game Simulation

A standalone, browser-based visual simulator for learning how Address Resolution Protocol (ARP) resolves IPv4 addresses to MAC addresses on a local network.

## Live Demo

[Open the ARP simulator](https://computer-network-presentation.vercel.app/arp_visual_simulator.html)

## Features

- Six-host network connected through a LAN switch
- Animated ARP broadcast requests and unicast replies
- Switch port activity lights and host response highlighting
- Live ARP cache showing learned IP-to-MAC mappings
- Mission scoring for discovering hosts
- Responsive, light-themed mobile frame

## Run

Open `index.html` in a modern web browser or visit the project root on Vercel. The root page redirects to `arp_visual_simulator.html`. No build step or dependencies are required.

Select a target host and choose **Send ARP** to watch the request, response, and cache update. Use **Reset** to restart the mission and clear the cache.
