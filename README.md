# Update iOS Plist

This action update or add a custom key in the Info.plist file for your iOS projects.

## Inputs

### `info-plist-path`

**Required** The relative path for the Info.plist file.

### `key-name`
  
**Required** The name of the user defined key.

###  `key-value`
    
**Required** The value of the user defined key

###  `print-file`

Output the Info.plist file in console before and after update.

## Usage

```yaml
- name: Update iOS Plist
  uses: dppeak/update-ios-plist-action@v1.0.0
  with:
    info-plist-path: './path_to_your/Info.plist'
    key-name: 'UserCustomKey'
    key-value: 'some value'
    print-file: true
```
