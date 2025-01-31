# Industrial Light AOV Splitter / 工业化灯光AOV创建器

### 更细化的灯光aov，工业化灯光AOV创建器

### Materialized light group auto builder for blender
======================

![屏幕截图 2025-01-31 233806](https://github.com/user-attachments/assets/39c8bdc9-a9c3-46f8-bbdf-9fe23bd8cf6a)

**插件面板位置：属性面板→视图层**

**Plugin panel location: Properties Panel→View Layer**

======================

目前支持3.6 - 最新版 Supports blender 3.6 - newest by now (2025.01.31)

通过基本无感的方式，自动给符合条件的灯创建灯光组，把灯光分离成diffuse, specular, transmission, volume四个通道(如diffuse_env, specular_env...)，以取得与行业接轨的可控性（合成软件内）。

Automatically create light groups for eligible lights in a seamless manner, separating the lights into four channels: diffuse, specular, transmission, and volume (e.g., diffuse_env, specular_env...), to achieve industry-standard controllability during the compositing stage.

---
**Update Log:**
2025.1.31: version 0.5.0

1. initial release, with basic functions.

---

### HOW TO USE:

**1. Blender light group aovs are stored at viewlayer level, so this plugin runs per viewlayer by now (in 4.4 there will be a new method to create all light groups in a scene). **
**2. Put your lights in collections whose name starts with "lgt_". **
**3. Naming your light properly with letters and numbers only. Do not use any "_" "." **
**4. If you want to reuse light group between multiple lights, just duplicate the lights and keep their auto-generated ".001" number suffix, they'll be ignored and revert back to the desired name. **
