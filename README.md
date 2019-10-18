
#touchpadの名前を見つける
例

```
$xinput
⎡ Virtual core pointer                    	id=2	[master pointer  (3)]
⎜   ↳ Virtual core XTEST pointer              	id=4	[slave  pointer  (2)]
⎜   ↳ ETPS/2 Elantech Touchpad                	id=13	[slave  pointer  (2)]
```
 この場合"ETPS/2 Elantech Touchpad"がtouchpadの名前

#touchpad_on_off.shの実行
touchpad_on_off.shがある階層で

```
chmod 755 touchpad_on_off.sh
```
touchpad_on_off.shがある階層で
これ以降以下のコマンドを実行するたびに切り替わる

```
./touchpad_on_off.sh "ETPS/2 Elantech Touchpad"
```
