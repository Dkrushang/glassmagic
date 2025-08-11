# Glassmagic

Glassmagic is an Android library extracted from the Blueprint project and rebranded for custom use.  
It can be integrated into any Android app via [JitPack](https://jitpack.io).

---

## 📦 Installation

### Step 1 — Add JitPack to your repositories
In your **root** `settings.gradle` or `build.gradle`:
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}
```

### Step 2 — Add the dependency
Replace `<your-username>` with your GitHub username and `<version>` with the tag you release.
```gradle
dependencies {
    implementation 'com.github.<your-username>:glassmagic:<version>'
}
```

---

## 🚀 Usage
Import the package in your Kotlin or Java code:
```kotlin
import dev.krushang.glassmagic.app.YourClassName
```

---

## 🏷 Versioning
We recommend using semantic versioning:  
- **MAJOR.MINOR.PATCH** — e.g., `1.0.0`

---

## 🛠 Building Locally
If you want to test the library locally without JitPack:
```bash
./gradlew assembleRelease
```

---

## 📄 License
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
