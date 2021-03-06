# Recommendation-System-Analysis
This project was created for the subject "web mining" and was a way to demonstrate the strengths of different types of recommendation systems.
## Dataset link
  + https://www.kaggle.com/gspmoreira/articles-sharing-reading-from-cit-deskdrop
    + This rich and rare dataset contains a real sample of 12 months logs (Mar. 2016 - Feb. 2017) from CI&T's Internal Communication platform (DeskDrop). I contains about 73k logged users interactions on more than 3k public articles shared in the platform.
    + This dataset features some distinctive characteristics:
      + Item attributes: Articles' original URL, title, and content plain text are available in two languages (English and Portuguese).
      + Contextual information: Context of the users visits, like date/time, client (mobile native app / browser) and geolocation.
      + Logged users: All users are required to login in the platform, providing a long-term tracking of users preferences (not depending on cookies in devices).
      + Rich implicit feedback: Different interaction types were logged, making it possible to infer the user's level of interest in the articles (eg. comments > likes > views).
      + Multi-platform: Users interactions were tracked in different platforms (web browsers and mobile native apps)
