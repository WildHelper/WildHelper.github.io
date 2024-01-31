---
layout: default
permalink: /en.html
---

WildHelper is a school administrative assistant supporting grade inquiry, timetable viewing, examination schedule checking, and score notification alerts, exclusively for current students and alumni of designated schools.

This project is open-sourced under the [GNU Affero GPL v3.0](https://github.com/WildHelper/WildHelper.github.io/raw/master/LICENSE) license, allowing anyone to freely modify and redistribute the software under this license's constraints. If the program is modified and provided as a service over the network, the complete source code of the modifications must be publicly disclosed under the same license.

The project aims to enhance the mobile administrative experience for students; however, within the limits of applicable law, the project does not assume any liability. Users must bear all risks, for details, please see the [GNU Affero GPL v3.0](https://github.com/WildHelper/WildHelper.github.io/raw/master/LICENSE).

<img src="https://user-images.githubusercontent.com/6601455/87389305-18a0fc00-c5d9-11ea-8329-028038f6668d.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389413-48500400-c5d9-11ea-84f5-24d8fb8480af.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389498-6c134a00-c5d9-11ea-88cc-5c378fe2b105.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389508-6fa6d100-c5d9-11ea-9d65-1a8d2a772a64.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389513-71709480-c5d9-11ea-8869-ec8adcb31124.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389522-733a5800-c5d9-11ea-99a8-2681f5afa489.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389527-76354880-c5d9-11ea-8f70-244c7809faf8.PNG" width="200" />
<img src="https://user-images.githubusercontent.com/6601455/87389532-77ff0c00-c5d9-11ea-96cf-df8c1cc257b0.PNG" width="200" />

## Current Projects

- [WildHelper](https://github.com/WildHelper): GitHub project homepage
  - [MiniProgram](https://github.com/WildHelper/MiniProgram): Mini Program
  - [Server-PHP](https://github.com/WildHelper/Server-PHP): Backend - PHP Version
  - [WildHelper.github.io](https://github.com/WildHelper/WildHelper.github.io): Official Website
- [ZE3kr/BJUT-Grade-Distribution-2020](https://github.com/ZE3kr/BJUT-Grade-Distribution-2020): WildHelper (formerly BJUT Helper) full data on course statistics at Beijing University of Technology.

## Core Features

- **Grade Inquiry:** Automatically calculates weighted average scores, GPA, course count, total credits, and pass rate for each semester, minor/dual degrees, and primary degree. It automatically handles special cases like retakes, makeup exams, and failures; displays score details grouped by teacher, course type, course code, and course credits, and supports sorting and searching; supports score sharing.
- **Timetable Viewing:** Automatically highlights courses based on the current week; supports term selection; supports timetable sharing.
- **Examination Schedule Checking:** Displays exam subjects, exam times, and exam locations during exam week.
- **Course Selection Guidance:** Utilizes big data to display basic information such as the average score and GPA for each course; automatically generates course score distribution histograms; supports filtering by course type, sorting by scores, and searching by course name.
- **Score Notification:** Supports subscription for score notifications, alerting students immediately when scores are released.

Some schools may only offer partial functionality.

## Technical Highlights

- **Complete separation of front and backend**, universal RESTful API.
- Developed with **native** Mini Program, supports **preloading** of WeChat data, **periodic** updates.
- Real-time automatic data retrieval in cooperation with schools.
- Supports **alumni verification**, 100% guarantee of user authenticity, simpler and more user-friendly than the student network.
- User histograms are automatically drawn using **Canvas2D**.
- Grayscale feature **toggle**.
- Automatic error log **reporting**, WeChat group alerts for convenient emergency maintenance.
- User feedback button for instant customer service integration.
- Uses **end-to-end encryption** (AES-256-GCM), intermediaries (including WeChat) cannot access any user data.
- Non-course selection week users can only see their selected courses.
- Server **never stores user passwords**.
- **Authorization revocation mechanism**, users can completely delete all data at any time.
