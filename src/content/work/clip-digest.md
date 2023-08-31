---
title: Clip Digest
publishDate: 2023-11-02 00:00:00
img: /assets/clip-digest.jgp
img_alt: A room filled with gaming chairs, monitors, and a computer
description: |
  Developed 'Clips Digest' for Twitch's non-gaming creator managers using React.js.
tags:
  - Dev
  - React
  - Node
---

**Code**: Private

The project is an intuitive platform designed to enable creator managers to swiftly access, review, and blend in with the dynamic content environment of the creators they supervise. This interface is envisaged as a tool for expediting and improving the quality of feedback on the material produced by creators, which eventually enhances the entire content acquisition and development experience.

The interface is built with users' convenience in mind. It allows creator managers to input the list of creators they manage and provides a digest of their respective VODS and clips, keeping managers updated on the latest content. Moreover, the clip digest can be refreshed to fetch the most recent clips, and it displays crucial information like clip title, broadcaster name, game name, created date, and a clip-previewing thumbnail. This ensures a thorough understanding of the material.

To maintain the seamless functionality of the platform, the interface handles Twitch API errors and rate limits effectively. This allows the uninterrupted utilization of the application. Further, the platform is designed to be responsive and compatible on a range of devices and window sizes, ensuring managers can review clips anytime, anywhere. Significant focus is laid on security to allow managers to securely log in using their Twitch accounts and have their sessions persisted across multiple visits. The infrastructure respects individual API rate limits by employing user-specific Twitch API keys for requests.

The technology stack comprises React.js for a robust and interactive user interface, Express.js, and Node.js for managing server-side logic and dealing with data processing or transformations. MongoDB is utilized for secure user authentication token storage and session management.
The ultimate aim remains the efficient feedback process and improved acquisition experience. Also, forward plans include API augmentation, feature enhancements, and wider compatibility with a variety of devices, substantiating the project's scalability. Please note that this project's source code privacy is maintained due to confidentiality and company policies.