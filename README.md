# Decrypted-
 InputBox("Data to encrypt","Enter data to encrypt")  $e_data = _Crypt_EncryptData($data, $g_hKey, $CALG_USERKEY) MsgBox(0,"Encrypted Data", $e_data)  $de_data = _Crypt_DecryptData($e_data, $g_hKey, $CALG_USERKEY) MsgBox(0,"Decrypted Data", BinaryToString($de_data))
