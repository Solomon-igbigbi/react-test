# FrontEnd Coding Challenge 🎧

# Goals/Outcomes ✨
- To test knowledge of consuming APIs and handling responses.
- Loading state and knowing where and how to make multiple API calls efficiently.
- Should be able to play/pause a music.
- Your ability to self research.
- Problem solving skills

# Hint
- Deploy to heroku


# Pre-requisites ✅
- Add your Deezer client ID & secret to `env`
  - Note. **Never add this type of config to version control. This would usually come from your build server.**

# Requirements 📖
- Develope the UI/UX
  - Use the design screen provided below in this markdown.
- Fetch and display *Released This Week* songs
  - Use the API path `new-releases`
- Fetch and display *Featured Playlists*
  - Use the API path `featured-playlists`
- Fetch and display *Browse* genres
  - Use the API path `categories`
- Loading state/UI *(optional, current UX is already clean)*

Deezers API Documentation: [https://developers.deezer.com/api](https://developers.deezer.com/api)
<br>
Deezers API: [https://api.deezer.com/chart](https://api.deezer.com/chart)
<br>
<br>

# Think about 💡
- Taking a look at the Deezer API documentation
- Do you resolve each API request one after the other or in parallel?
- Where do you make the API requests?
- How much logic do you offload out of the UI components?

<!-- # What's Already Been Done 🏁
- UI/UX for all elements, including previews (mobile responsive)
- A Deezer request helper (`makeRequest.js`) -->

# Screenshots 🌄

![screenshot-desktop](https://puu.sh/GwPLE/3be580156a.png)
![screenshot-mobile](https://puu.sh/GwPLS/0bcb566d23.png)
