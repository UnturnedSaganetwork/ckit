# ckit
/ckit (isim) (süre) false 0 normal kit ekler

örnek: /ckit polis 360 false 0 

/dkit isim kit siler

/ckit (isim) (süre) false (miktar) oyun parasi ile parali kit yapma 

/ckit (isim) (süre) ture 0 insan öldüğü zaman direk bir daha kit çekebilir 

araç kiti 
/ckit apc süre false 0
/editkit apc additem vahicle id

xp kiti
/ckit isim süre false 0
/editkit isim additem xp isim

perm:

<Permission Cooldown="0">essentials.kit.isim</Permission>

(isim yerine kitin adı)

örnek:

    <Group>
      <Id>polis</Id>
      <DisplayName>polis</DisplayName>
      <Prefix>[polis]</Prefix>
      <Suffix />
      <Color>F7FFFF</Color>
      <Members />
      <Priority>100</Priority>
      <Permissions>
        <Permission Cooldown="0">essentials.kit.polis</Permission>
      </Permissions>
    </Group>

