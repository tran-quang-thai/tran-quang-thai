<div align="center">

<!-- Avatar tròn neon (tự động lấy từ GitHub) -->
<img src="?size=200" width="140" height="140" style="border-radius:50%; border: 4px solid #00d4ff; box-shadow: 0 0 20px #00d4ff;" alt="avatar"/>

<br><br>

```protobuf
message YourName {
  required string name        = "Tên thật của bạn";
  required int32  age         = ??;                      // điền tuổi
  required string vibe        = "Lười nhưng nguy hiểm";

  message RealSkills {
    required uint32 RootMe_Jailbreak   = 96;  // pro thật mà
    required uint32 GitHub_Game        = 92;  // đang flex README đây còn gì
    required uint32 FixPC_GodMode      = 94;  // BitLocker, temp, BIOS...
    required uint32 KiếmTiềnOnline     = 99;  // spam comment, affiliate king
    required uint32 Meme_Vietnamese    = 100;
    required uint32 Caffeine_Resistance= 88;
  }

  message Currently {
    optional string mood        = "Lười nhưng vẫn phải đẹp";
    optional string doing       = "Flex README cho cả thế giới xem";
    optional string coffee      = "Cốc thứ 5 và vẫn tỉnh";
  }
}
