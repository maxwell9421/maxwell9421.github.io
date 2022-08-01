
# Methods Template (调用方法名字)

Implemented in:
[ModuleTemplate](md/api/ModuleTemplate.md)

- Declaration 声明
  
  ```csharp
  public void ActivateCurrentOffMeshLink(bool activated);
  ```

- Parameters 参数
  
  | 参数名称      | 参数类型 | 参数说明                   |
  | --------- | ---- | ---------------------- |
  | activated | bool | Is the link activated? |
  |           |      |                        |
  |           |      |                        |

- Description 描述
  
  Enables or disables the current off-mesh link.
  
  This function activates or deactivates the off-mesh link where the agent is currently waiting. This is useful for granting access to newly discovered areas of the game world or simulating the creation or removal of an obstacle to an area.

- Example 示例

```csharp
print("hello world!");
```
