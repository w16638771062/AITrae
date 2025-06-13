# 项目文档

## 代码结构
### 根目录
包含 `.gitignore`、`pom.xml`、`src` 目录、`start.sh` 和 `upload` 目录。

### `src` 目录
- `main` 子目录：包含 `java` 和 `resources` 两个子目录。

### `src/main/java` 目录
包含 `com` 子目录。

### `src/main/resources` 目录
包含 `application.properties`、`logback-spring.xml` 文件以及 `mapper` 目录。

### `src/main/resources/mapper` 目录
包含多个 XML 文件，如 `CommentMapper.xml`、`OrderMapper.xml`、`OverviewMapper.xml`、`ThingCollectMapper.xml`、`ThingMapper.xml`、`ThingWishMapper.xml` 和 `UserMapper.xml`。

## 代码文档规范
### 注释规范
Java 项目文档开头注释规范：类注释包含类描述和作者，方法注释包含功能、参数和返回值说明 <mcreference link="https://blog.csdn.net/SL_World/article/details/78245722" index="4">4</mcreference>。

### 文档生成方法
- 使用 Apache POI 库可实现 Java 生成 Word 模板，用于自动化报告、合同生成等场景 <mcreference link="https://blog.csdn.net/weixin_42443533/article/details/144048757" index="2">2</mcreference>。
- 基于模板的 Java 代码生成详细设计文档步骤：制定模板、解析模板、获取代码数据结构、输出文档 <mcreference link="https://www.xjishu.com/zhuanli/55/202210838946.html" index="5">5</mcreference>。
- 使用 `org.apache.velocity` 工具类可根据自定义模板生成代码，需引入依赖 <mcreference link="https://blog.csdn.net/qq_20009015/article/details/104171000" index="3">3</mcreference>。