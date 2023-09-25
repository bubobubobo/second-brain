
### Info.plist의 UISupportedInterfaceOrientations

해당 key 값으로 앱의 orientation을 제한할 수 있다. 아래처럼 설정한 value들에 대해 orientation이 제한되며, default로 왼쪽, 오른쪽, 아래 회전이 제한되어 회전할 수 없다.

```tsx
<key>UISupportedInterfaceOrientations</key>  
<array>  
   <string>UIInterfaceOrientationLandscapeLeft</string>  
   <string>UIInterfaceOrientationLandscapeRight</string>  
   <string>UIInterfaceOrientationPortraitUpsideDown</string>  
</array>
```




