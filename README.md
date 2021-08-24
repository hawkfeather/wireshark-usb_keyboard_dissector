# Wireshark USB Keyboard Dissector Plugins

一个解析 USB 键盘流量的 Wireshark 插件，在协议详情视图里添加对 HID Data 数据的解析，在协议视图的 Info 列添加显示键码对应的名称。

> 键码映射表参照文档 https://usb.org/sites/default/files/hut1_22.pdf

## Usage

```
# wireshark filters
usb
usb_keyboard
usb_keyboard.key_code != 0
```

![img](https://github.com/hawkfeather/wireshark-usb_keyboard_dissector/blob/main/screenshot/screenshot-01.png)

![img](https://github.com/hawkfeather/wireshark-usb_keyboard_dissector/blob/main/screenshot/screenshot-02.png)

## License

MIT
