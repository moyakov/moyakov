<div align="center">
    <h3>🎬 Сцена загрузки системы...</h3>
    
    <div style="font-family: 'Cascadia Code', monospace; color: #00FFFF; text-align: center; max-width: 600px; margin: 40px auto; padding: 20px; background: rgba(0, 0, 0, 0.3); border-radius: 10px; border: 1px solid #00FFFF;">
    
    <div style="text-shadow: 0 0 10px #00FFFF, 0 0 20px #0077FF;">
        <div style="color: #FF6B8B; font-size: 2rem; font-weight: bold; letter-spacing: 2px;">
            РУСЛАН КУЛИЕВ
        </div>
        
        <div style="color: #7F52FF; font-size: 1.5rem; margin: 10px 0;">
            ⚡ Android Developer
        </div>
        
        <div style="color: #00FFFF; font-size: 1rem; margin-top: 20px;">
            <div>📍 Москва, Россия</div>
            <div>🎓 МФЮА | Computer Science</div>
            <div>🚀 Junior → Middle Level</div>
        </div>
    </div>
    
    <div style="margin-top: 30px;">
        <span style="color: #3DDC84; animation: pulse 1s infinite;">●</span>
        <span style="color: #7F52FF; animation: pulse 1s infinite 0.3s;">●</span>
        <span style="color: #00FFFF; animation: pulse 1s infinite 0.6s;">●</span>
        <span style="color: #FF6B8B; animation: pulse 1s infinite 0.9s;">●</span>
    </div>
    
    </div>
</div>

<style>
    @keyframes pulse {
        0%, 100% { opacity: 0.3; transform: scale(0.8); }
        50% { opacity: 1; transform: scale(1.2); }
    }
    
    @keyframes neon-glow {
        0%, 100% { text-shadow: 0 0 10px #00FFFF; }
        50% { text-shadow: 0 0 20px #00FFFF, 0 0 30px #0077FF; }
    }
</style>

  
  <br>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=32&duration=3000&pause=1000&color=00FFFF&width=500&lines=val+name+%3D+'Ruslan';val+role+%3D+'Android+Dev';Kotlin+%7C+Jetpack+Compose;Connect+on+Telegram" alt="Typing Animation" />

  <p align="center">
    <img src="https://img.shields.io/badge/Status-Coding%20the%20Future-00FFFF?style=for-the-badge&logo=visual-studio-code&logoColor=white&labelColor=0d1117&borderColor=0077FF" alt="Status" />
    <img src="https://img.shields.io/badge/Mode-Creative%20Flow-7F52FF?style=for-the-badge&logo=creative-commons&logoColor=white&labelColor=0d1117&borderColor=7F52FF" alt="Mode" />
  </p>

  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" alt="Rainbow divider" width="100%" height="2" />
</div>

## 🛰️ **Системный профиль**
<p align="justify">
  <img src="https://img.shields.io/badge/Уровень-Junior%20Developer-7F52FF?style=flat-square&logo=rocket&logoColor=white&labelColor=0d1117" alt="Level" />
  <img src="https://img.shields.io/badge/Направление-Android%20Development-3DDC84?style=flat-square&logo=android&logoColor=white&labelColor=0d1117" alt="Focus" />
</p>

```kotlin
data class DeveloperProfile(
    val name: String = "Ruslan Kovalev",
    val role: String = "Android Developer",
    val level: String = "Junior → Middle",
    val location: String = "Moscow, RU",
    val education: String = "MFUA | Computer Science",
    val status: Status = Status.CODING,
    val passion: String = "Creating mobile magic ✨"
)

enum class Status {
    CODING, LEARNING, INNOVATING, DEBUGGING
}

val myProfile = DeveloperProfile().apply {
    println("🚀 Профиль загружен: $name")
    println("💼 Специализация: $role")
    println("📚 Текущий статус: ${status.name}")
}
