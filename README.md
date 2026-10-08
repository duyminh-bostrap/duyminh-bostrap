<div align="center">

<img src="assets/mik-studio-logo.png" alt="Mik Studio" height="96" />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:ff8a00,50:ff5a1f,100:d93a1a&height=220&section=header&text=Nguy%E1%BB%85n%20Duy%20Minh&fontSize=56&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Founder%20%C2%B7%20Mik%20Studio&descSize=22&descAlignY=60" alt="Nguyễn Duy Minh" />

<a href="https://github.com/duyminh-bostrap">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=FF6A1A&center=true&vCenter=true&width=640&lines=Projection+Mapping+%F0%9F%8E%A5;Interactive+Installation+%E2%9C%A8;AV+Control+%26+Tooling+%F0%9F%93%BD%EF%B8%8F;Computer+Vision+%26+AR+%F0%9F%91%81%EF%B8%8F" alt="Typing animation" />
</a>

📍 Hà Nội, Việt Nam

[![Email](https://img.shields.io/badge/Email-duyminh.bostrap@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:duyminh.bostrap@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Minh%20Nguyễn%20Duy-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/minh-nguy%e1%bb%85n-duy-4584221b9/)
[![Facebook](https://img.shields.io/badge/Facebook-duyminh.bostrap-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/duyminh.bostrap)
[![Instagram](https://img.shields.io/badge/Instagram-duy._.minh-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/duy._.minh/)

<img src="https://komarev.com/ghpvc/?username=duyminh-bostrap&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile views" />
<a href="https://github.com/duyminh-bostrap?tab=followers"><img src="https://img.shields.io/github/followers/duyminh-bostrap?label=Followers&style=flat-square&logo=github" alt="Followers" /></a>

</div>

---

## 👋 Giới thiệu

Mình xây dựng các công cụ và trải nghiệm tương tác cho **sự kiện, triển lãm và show trình diễn** — từ phần mềm điều khiển máy chiếu, engine projection mapping cho đến những tiện ích nhỏ giúp một show vận hành ổn định.

Nền tảng ban đầu của mình là **Computer Vision & Augmented Reality** (Unity, Vuforia, Flutter, OpenCV). Hiện tại trọng tâm chuyển sang **hệ sinh thái Mik Studio**: bộ sản phẩm cho dân AV / interactive muốn làm việc nhanh, rõ ràng và không phụ thuộc phần mềm đắt đỏ.

- 🔭 Đang phát triển: **MikMap** (projection mapping + sensor calibration) và **MikMaster** (quản lý máy chiếu)
- 🌱 Đang học: Rust, WebRTC, pipeline realtime 4K
- 💬 Hỏi mình về: **Projection mapping · Interactive installation · AV control · Computer Vision · AR**
- 🤝 Mở cho hợp tác: dự án triển lãm, show tương tác, bảo trì hệ thống AV

---

## 🧩 Hệ sinh thái Mik Studio

```
                      ┌──────────────────────────┐
                      │        Mik Studio        │
                      └────────────┬─────────────┘
        ┌───────────────┬──────────┴─────┬─────────────────┐
     Mik Map        Mik Master        Mik Drop           EDID Kit
  Mapping engine   Điều khiển        Chia sẻ file       Ổn định output
  + sensor calib   máy chiếu AV      P2P qua Wi-Fi      cho show live
```

| Sản phẩm | Mô tả | Công nghệ | Repo |
|---|---|---|---|
| 🗺️ **MikMap** | Engine projection mapping kết hợp calibration sensor — *chạm vào vật thể thật, hiệu ứng nổ đúng chỗ đó*. Lưới clip kiểu Resolume, keystone/mesh warp, 4K HAP, UI song ngữ Việt/Anh. | C++20 · OpenGL · Dear ImGui · openFrameworks · CMake | [MikMap](https://github.com/duyminh-bostrap/MikMap) · [MikMap_Web](https://github.com/duyminh-bostrap/MikMap_Web) · [Mikmap_UI](https://github.com/duyminh-bostrap/Mikmap_UI) |
| 🎛️ **MikMaster** | Web app desktop điều khiển & quản lý nhiều máy chiếu AV theo phân cấp *Project → Group → Projector*: quét IP, lệnh, trạng thái, test pattern, lens. | React 19 · TypeScript · Vite · Tailwind v4 · Vitest · Playwright | [MikMaster](https://github.com/duyminh-bostrap/MikMaster) · [Releases](https://github.com/duyminh-bostrap/MikMaster-releases) |
| 📡 **MikDrop** | Chia sẻ ảnh/tệp P2P giữa iPhone, Android, Mac, Windows, Linux qua Wi-Fi cục bộ, chỉ cần trình duyệt — kiểu AirDrop, dùng WebRTC. | Node.js · WebRTC · PWA | [MikDrop](https://github.com/duyminh-bostrap/MikDrop) |
| 🔒 **EDID Kit** | Hướng dẫn & script khoá EDID, giữ output máy chiếu / màn LED / virtual output ổn định trên Windows và macOS khi chạy show. | Docs · Scripts | [EDID](https://github.com/duyminh-bostrap/EDID) |
| 🎨 **Portfolio** | Trang portfolio cá nhân và Mik Studio. | TypeScript | [Mike-Portfolio](https://github.com/duyminh-bostrap/Mike-Portfolio) · [Portfolio](https://github.com/duyminh-bostrap/Portfolio) |

### 🧪 Khác

[Show-Controller](https://github.com/duyminh-bostrap/Show-Controller) · [TouchDesigner](https://github.com/duyminh-bostrap/TouchDesigner) · [Travel_Planner](https://github.com/duyminh-bostrap/Travel_Planner)

---

## 🛠 Công nghệ

<div align="left">

**Realtime & đồ hoạ**
<br>
<img src="https://skillicons.dev/icons?i=cpp,c,cs,unity,unreal,rust,opencv,pytorch,tensorflow" alt="graphics" />

**Web & ứng dụng**
<br>
<img src="https://skillicons.dev/icons?i=react,ts,js,nodejs,vite,tailwind,flutter,dart,swift,java" alt="web" />

**Dữ liệu, hạ tầng & công cụ**
<br>
<img src="https://skillicons.dev/icons?i=python,mongodb,firebase,aws,postman,git,github,vscode,ai,ps" alt="tools" />

</div>

---

## 📊 GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=duyminh-bostrap&show_icons=true&count_private=true&theme=react&hide_border=true&bg_color=0D1117" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=duyminh-bostrap&langs_count=8&count_private=true&layout=compact&theme=react&hide_border=true&bg_color=0D1117" alt="Top languages" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=duyminh-bostrap&bg_color=0D1117&color=FF6A1A&line=6a5acd&point_color=ff4fa3&area=true&hide_border=true" alt="Activity graph" />

<img src="https://streak-stats.demolab.com/?user=duyminh-bostrap&theme=github-dark&hide_border=true&background=0D1117" alt="Streak" />

<sub>Top languages chỉ phản ánh mã nguồn công khai, không đại diện cho kinh nghiệm hay kỹ năng.</sub>

</div>

---

<div align="center">

*Làm show thì phải ổn định. Làm công cụ thì phải dễ dùng.* ⚡

📫 **duyminh.bostrap@gmail.com**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:d93a1a,50:ff5a1f,100:ff8a00&height=120&section=footer" alt="" />

</div>
