---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: The Latest Upcoming Tournament
      text: The Whale Cup and Whale's Winter Weekend Wonderland are mahjong tournaments to find the best tile slinger in an open format. All are welcome but only the strong and lucky will survive. Thankfully Riichi City sponsors us and helps contribute to the prize pool, which I am super grateful for since their API is grand.. and they don't threaten to ban me for using said API like some other clients.<br /> <br />Anyways! Feel free to donate to the next tournament prize pool or ignore this and simply register, but please read the rules.
      primary_action:
        text: Donation to Prize Pool
        url: https://ko-fi.com/overlordwhale 
        icon: sparkles
      secondary_action:
        text: Just take me to the Discord
        url: https://discord.gg/9qt336srFz
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: WhaleShutterStock.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "Over 300"
          description: |
            Players in our last tournament
        - statistic: "4k+"
          description: |
            Amount of Games
        - statistic: "7k+"
          description: |
            Amount of Deal-ins
        - statistic: "16"
          description: |
            Amount of Yakuman's
        - statistic: "9k+"
          description: |
            Amount of Riichi's
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: currenttournament
    content:
      items:
        - title: The Whale Cup
          text: Paid by Riichi City and Whale's money
          feature_icon: check
          features:
            - A no entry fee tournament
            - Incredibly easy registeration process 
            - All skill levels welcomed!
          # Upload image to `assets/media/` and reference the filename here
          image: WhaleCupPart1-2025.png
          button:
            text: Read the rules
            url: https://docs.google.com/document/d/1CrKrqJZvPQ4LJ9Hh12LC82ITRG05qGz3F3r-pF_svvU/edit?usp=sharing
        - title: Other Rewards
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - Placement based rewards
            - Play just 1 game for the tileback and playmat
            - I like writing in three's
          # Upload image to `assets/media/` and reference the filename here
          image: WhaleCupPart2-2025.png
          button:
            text: Register at the Discord
            url: https://discord.gg/9qt336srFz
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
