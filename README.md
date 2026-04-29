<div align="center">                                                                                                                             
                                                                                                                                                   
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Pr
  akhar%20Dubey&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=📱%20React%20Native%20Developer%20%7C%20Mobile%20Craftsman&desc
  AlignY=62&descAlign=50&descSize=20"/>                                                                                                            
                            
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&w
  idth=700&lines=📱+React+Native+Developer;⚡+Building+apps+for+millions+of+users;🎨+60fps+animations+%26+silky+smooth+UX;🔧+Kotlin+%7C+Swift+%7C+T
  urboModules+%7C+JSI;🚀+Shipping+to+Play+Store+%26+App+Store" />                                                                                  
                            
  <br/>

  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/prakhardubey1
  3)
  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/prakharcodehere)        
  [![Profile Views](https://komarev.com/ghpvc/?username=prakharcodehere&style=flat-square&color=6e40c9)](https://github.com/prakharcodehere)       
                                                                                                                                                   
  </div>                                                                                                                                           
                                                                                                                                                   
  ---                       

  ```bash
  $ npx create-prakhar-app
  ```

  ```
    Checking environment...

    ✓  react-native        0.73+    — ready
    ✓  typescript          5.0      — ready                                                                                                        
    ✓  reanimated          3.x      — 60fps guaranteed
    ✓  new-architecture    JSI      — cutting edge                                                                                                 
    ✓  apps-shipped        10+      — production battle-tested                                                                                     
    ✓  users-served        1M+      — and counting
                                                                                                                                                   
    🚀  Hello, World. Let's build something amazing.
  ```                                                                                                                                              
   
  ---                                                                                                                                              
                            
  <img align="right" width="280" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"/>                                                
   
  ## 🧑‍💻 About Me                                                                                                                                   PR #246 · esc to interrupt
                            
  Hello! I'm **Prakhar Dubey**, a **React Native Developer** shipping apps to millions.                                                            
   
  - 📱 Building production mobile apps at scale                                                                                                    
  - ⚡ Obsessing over 60fps animations & silky UX
  - 🎨 Pixel-perfect UI/UX from Figma straight to device
  - 🔧 Custom native modules in Kotlin & Swift
  - 🧠 Deep-diving into RN New Architecture & TurboModules                                                                                         
  - 🚀 Shipped apps across Play Store & App Store
                                                                                                                                                   
  <br clear="both"/>        

  ---

  ## ✍️  How I Think About Animations                                                                                                               
   
  ```tsx                                                                                                                                           
  // Reanimated 3 — the way I build smooth UX 🎨
  const SwipeCard = () => {
    const translateX = useSharedValue(0);
    const rotate    = useSharedValue(0);
                                                                                                                                                   
    const gesture = Gesture.Pan()
      .onUpdate((e) => {                                                                                                                           
        translateX.value = e.translationX;
        rotate.value     = e.translationX / 20;
      })
      .onEnd(() => {
        translateX.value = withSpring(0, { damping: 15 });                                                                                         
        rotate.value     = withSpring(0);
      });                                                                                                                                          
                            
    const animatedStyle = useAnimatedStyle(() => ({
      transform: [
        { translateX: translateX.value },                                                                                                          
        { rotate: `${rotate.value}deg` },
      ],                                                                                                                                           
    }));                    

    return (
      <GestureDetector gesture={gesture}>
        <Animated.View style={[styles.card, animatedStyle]} />
      </GestureDetector>                                                                                                                           
    );
  };                                                                                                                                               
  ```                       

  ---

  <img align="left" width="240" src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif"/>                                                 
   
  ## 📱 React Native Stack                                                                                                                         
                            
  - **Navigation** — React Navigation 6, Deep Linking, Universal Links
  - **Animations** — Reanimated 3, Shared Elements, Lottie, Skia
  - **State** — Redux Toolkit, Zustand, React Query                                                                                                
  - **Native** — Kotlin bridges, Swift modules, TurboModules, JSI
  - **Performance** — Hermes, New Architecture, Bundle Splitting                                                                                   
  - **DevOps** — Fastlane, EAS Build, Sentry, CodePush, AppsFlyer
                                                                                                                                                   
  <br clear="both"/>
                                                                                                                                                   
  ---                       

  ## 💻 Technologies

  <div align="center">

  ![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)                                  
  ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)                                  
  ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)                                                
  ![Redux](https://img.shields.io/badge/Redux-593D88?style=flat-square&logo=redux&logoColor=white)                                                 
  ![Reanimated 3](https://img.shields.io/badge/Reanimated_3-FF6584?style=flat-square&logo=react&logoColor=white)                                   
  ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)                                              
  ![Swift](https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white)
  ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)                                           
  ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)                                           
  ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)                                        
  ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)                                              
  ![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black)
  ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)                                                       
  ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)                                                 
  ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)                                
                                                                                                                                                   
  </div>                    
                                                                                                                                                   
  ---                       

  ## 📊 Statistics

  <div align="center">

  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=prakharcodehere&show_icons=true&theme=github_dark&hide_border=true&incl
  ude_all_commits=true&count_private=true&title_color=58A6FF"/>
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com?user=prakharcodehere&theme=github-dark-blue&hide_border=true"/>           
                                                                                                                                                   
  <img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=prakharcodehere&theme=github_dark&hide_border=true&layout=co
  mpact&langs_count=8&title_color=58A6FF"/>                                                                                                        
                                                                                                                                                   
  </div>                    

  ---

  ## 🏆 Trophies

  <div align="center">                                                                                                                             
   
  [![Trophies](https://github-profile-trophy.vercel.app/?username=prakharcodehere&theme=onestar&no-frame=true&no-bg=true&margin-w=8&row=1)](https:/
  /github.com/ryo-ma/github-profile-trophy)
                                                                                                                                                   
  </div>                    

  ---
  ## 📈 Contribution Graph
                          
  <div align="center">
                      
  [![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=prakharcodehere&bg_color=0d1117&color=58A6FF&line=58A6FF&point=
  FFFFFF&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)                                               
                                                                                                    
  </div>                                                                                                                                           
                            
  ---
     
  ## 🎯 Profile Summary
                                                                                                                                                   
  <div align="center">
                                                                                                                                                   
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=prakharcodehere&theme=github_dark" width="98%"/>
                                                                                                                                                   
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=prakharcodehere&theme=github_dark" width="32%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=prakharcodehere&theme=github_dark"             
  width="32%"/>                                                                                                                        
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=prakharcodehere&theme=github_dark&utcOffset=5.5"    
  width="32%"/>                                                                                                                                 
                                                                                                                                                   
  </div>                    
                                                                                                                                                   
  ---                       
     
  ## 🌐 3D Contribution Calendar
                                
  <div align="center">
                      
  <img src="https://raw.githubusercontent.com/prakharcodehere/prakharcodehere/main/profile-3d-contrib/profile-night-rainbow.svg"/>
                                                                                                                                                   
  </div>
                                                                                                                                                   
  ---                       
     
  <div align="center">
                      
  ![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)
                                                                                                                                                   
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer"/>
                                                                                                                                                   
  </div>                    
