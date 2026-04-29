<div align="center">
  <img width="100%" src="https://raw.githubusercontent.com/prakharcodehere/prakharcodehere/main/header.svg"/>                                      
  </div>
                                                                                                                                                   
  ---                       

  <table>
  <tr>
  <td width="35%" align="center" valign="middle">
                                                                                                                                                   
  <img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" width="220"/>                                                              
                                                                                                                                                   
  </td>                                                                                                                                            
  <td width="65%" valign="top">

  ### Who Am I?

  I'm **Prakhar Dubey**, a React Native developer who lives and breathes mobile. I build apps that millions of real people open every single day — 
  products where a 16ms frame drop is a crime and a broken gesture is an insult.
                                                                                                                                                   
  My work lives at the intersection of **performance engineering** and **pixel-perfect design**. I write Kotlin bridge modules before breakfast,   
  ship Reanimated worklets before lunch, and untangle iOS build scripts for fun *(not really, but someone has to).*
                                                                                                                                                   
  Right now I'm deep in **RN New Architecture**, **TurboModules**, and **JSI** — because smooth is never smooth enough.                            
   
  </td>                                                                                                                                            
  </tr>                     
  </table>

  ---

  <div align="center">

  ### You can reach me here                                                                                                                        
   
  <a href="https://linkedin.com/in/prakhardubey13"><img                                                                                            
  src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>&nbsp;
  <a href="https://github.com/prakharcodehere"><img                                                                                                
  src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white"/></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=prakharcodehere&style=for-the-badge&color=a78bfa&label=PROFILE+VIEWS"/>
                                                                                                                                                   
  </div>
                                                                                                                                                   
  ---                       

  ## ⚡ Skills                                                                                                                                     
   
  ```                                                                                                                                              
  React Native   ████████████████████  Expert
  TypeScript     ████████████████████  Expert
  Reanimated 3   ██████████████████░░  Advanced                                                                                                    
  Redux/Zustand  ████████████████████  Expert
  React Query    ████████████████░░░░  Proficient                                                                                                  
  Kotlin         ████████████░░░░░░░░  Intermediate
  Swift          ██████████░░░░░░░░░░  Intermediate                                                                                                
  Node.js        ████████████████░░░░  Proficient
  ```                                                                                                                                              
                            
  ---                                                                                                                                              
                            
  ## ✍️  How I Build Smooth UX                                                                                                                      
   
  ```tsx                                                                                                                                           
  // Reanimated 3 — swipe card with spring physics 🎨
  const SwipeCard = () => {                                                                                                                        
    const translateX = useSharedValue(0);                                                                                                          
    const rotate     = useSharedValue(0);                                                                                                          
                                                                                                                                                   
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
                            
  <details>
  <summary>📱 <b>Full React Native Architecture</b></summary>
  <br/>                                                                                                                                            
   
  | Layer | Technology | Purpose |                                                                                                                 
  |:------|:-----------|:--------|
  | 🎨 UI | React Native + TypeScript | Pixel-perfect cross-platform UI |                                                                          
  | ✨ Animations | Reanimated 3 + Skia + Lottie | 60fps on the native thread |                                                                    
  | 🧭 Navigation | React Navigation 6 + Deep Linking | Seamless transitions |                                                                     
  | 🗃️  State | Redux Toolkit + Zustand + React Query | Global, local & server state |                                                              
  | 🔧 Native | Kotlin + Swift + TurboModules + JSI | Full device capability access |                                                              
  | ⚡ Performance | Hermes + New Architecture + Flipper | Sub-second cold starts |                                                                
  | 🚢 DevOps | Fastlane + EAS Build + CodePush | One-command store deployments |                                                                  
                                                                                                                                                   
  </details>                                                                                                                                       
                                                                                                                                                   
  ---                       

  ## 📊 My Contributions                                                                                                                           
   
  <div align="center">                                                                                                                             
                            
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=prakharcodehere&show_icons=true&theme=github_dark&hide_border=true&incl
  ude_all_commits=true&count_private=true&title_color=a78bfa"/>
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com?user=prakharcodehere&theme=github-dark-blue&hide_border=true"/>           
                                                                                                                                                   
  [![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=prakharcodehere&bg_color=0d1117&color=a78bfa&line=a78bfa&point=
  06b6d4&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)                                               
                                                                                                                                                   
  </div>                    

  ---

  <div align="center">

  > ⚠️  **Caution**                                                                                                                                 
  >
  > *Code is never finished. It only gets better.*                                                                                                 
  >                                                                                                                                                
  > *What you see here is built with obsession, late nights, and too much coffee.*
                                                                                                                                                   
  </div>                    
                                                                                                                                                   
  ---                       

  <div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:a78bfa,100:06b6d4&height=100&section=footer"/>
  </div>                                                                                                                                           
   
