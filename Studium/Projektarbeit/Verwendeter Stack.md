## 4.2 Verwendeter Stack  
Der verwendete Stack enthält Frameworks und Libraries des Ökosystems von der Open Source  
Gruppe Poimandres. Eine Open Source Initiative die sich besonders auf ReactJS fokussiert  
und neben Utilities für den generellen Gebrauch in React Anwendungen auch besonders viel  
Arbeit in eine ThreeJs Implementation in React steckt. Es folgt eine Auflistung der verwendeten  
Frameworks und Libraries um dann zu der konkreten Umsetzung über zu leiten.  
#### 4.2.1 Poimandres  
#### 4.2.2 react-three-fiber  
Das Kern Stück des Stacks und was die 3D Visualisierung ermöglicht ist react-three-fiber.  
Ein React Renderer für threeJS. Der Fokus dieser Implementation ist es die Funktionen von  
threeJS durch die Vorteile von React zu erweitern. Hierzu gehört das aufbauen der Szene durch  
wiederverwendbare und eigenständige Komponenten, die selbständig auf Zustandsänderungen  
reagieren können, interaktiv sind und können das existierende React Ökosystem nutzen. Es  
bietet mögliche Performance Vorteile gegenüber threeJS Anwendungen da die Komponenten  
ausserhalb von React in einem einheitlichen Renderloop partizipieren, wie auch die Verbesserung  
der Skalierbarkeit durch die inherenten Ablaufmanaging Fähigkeiten von React.  
Das folgende Codesnippet zeigt wie ein react-three-fiber aussieht. In dieser Implementation  
wird zu erst eine Box Komponente erstellt, der Properties übergeben werden können.. Diese  
Komponente erstellt eine Box Geometry mit einem Material in Orange. Dann wird im Mainloop,  
was die ReactDOM.render Funktion darstellt die Szene aufgebaut. Dafür wird zu erst die Canvas  
Komponente erstellt, diese mit Licht Komponenten befüllt und dann 2 Box Komponenten mit  
verschiedenen Positionen und Rotation erstellt. So kann bereits mit relativ wenig Code eine  
erste 3D Szene erstellt werden.

#### 4.2.3 react-three-flex  
#### 4.2.4 react-three-xr  
#### 4.2.5 react-three-drei  
#### 4.2.6 zustand  
#### 4.2.7 use-gesture