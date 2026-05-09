platform :ios do
  desc "ดึงใบรับรอง P12 และ MobileProvision"
  lane :get_certs do
    # ดึงใบเซอร์ Development
    get_certificates(
      type: "development",
      output_path: "output",
      p12_password: "1234" # รหัสสำหรับไฟล์ .p12 (ตั้งไว้ให้เผื่อพี่ต้องใช้)
    )
    # ดึงโปรไฟล์การติดตั้งแอป
    get_provisioning_profile(
      type: "development",
      output_path: "output"
    )
  end
end
