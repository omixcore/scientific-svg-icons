# Contributing | 贡献规范

Thank you for helping improve Scientific SVG Icons. 感谢参与完善本项目。

## Before adding an icon | 添加前

1. Check whether an equivalent icon already exists. 检查是否已有相同或近似图标。
2. Confirm that the asset is original or redistribution is explicitly permitted. 确认素材为原创或已获得明确再分发许可。
3. Record source, creator, and license in `metadata/icon-index.csv`. 在图标索引中记录来源、创作者和许可证。
4. Upload the editable SVG source, not only a screenshot or raster preview. 上传可编辑 SVG 源文件，不要只上传截图或位图。

## SVG requirements | SVG 要求

- Use a standalone SVG with a clear `viewBox`. 使用独立 SVG 并设置清晰的 `viewBox`。
- Keep paths and groups editable. 尽可能保持路径和图层可编辑。
- Do not include JavaScript, remote resources, tracking code, or embedded binaries. 不得包含脚本、远程资源、跟踪代码或嵌入式二进制文件。
- Include `<title>` and meaningful descriptions. 添加标题和有意义的描述。
- Use lowercase kebab-case filenames. 文件名使用英文小写 kebab-case 格式。

## Scientific and visual review | 科学性与视觉审核

- Verify biological structures, molecular labels, arrows, and regulatory relationships. 核对生物结构、分子名称、箭头和调控关系。
- Do not present schematic drawings as quantitative or experimentally validated data. 不得将示意图描述为定量数据或已验证的实验结果。
- Check that the SVG opens in browsers and remains editable in vector applications. 检查 SVG 能否在浏览器中打开，并可在矢量软件中编辑。

## Commit and versioning | 提交与版本

- Keep commits attributable to the repository owner or the actual human contributor. 提交应归属于仓库持有者或实际人工贡献者。
- Do not use bot or AI-agent identities as commit authors. 不使用 bot 或 AI agent 身份作为提交作者。
- Update the icon index whenever icons change. 图标发生变化时同步更新索引。
- Keep `VERSION` synchronized with the README. 保持 VERSION 与 README 版本一致。
