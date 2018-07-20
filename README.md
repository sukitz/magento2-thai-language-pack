# magento2-language-th-th  ![Progress](http://progressed.io/bar/90?title=completed)
Magento 2 Thai Language Pack 

## How to Install Thai Language Pack

### Download and install manually 
To download and install Thai pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package
[Download .zip](https://github.com/sukitz/magento2-language-pack/archive/master.zip)

#### Step 2: Unzip and upload
Unzip the compressed file and upload file ```th_TH.zip``` into ```app/i18n/sukit/th_TH/```

#### Step 3: Replace th_TH and Deploy

```php bin/magento i18n:pack -m replace -d app/i18n/sukit/th_th/th_TH.csv th_TH && php bin/magento setup:static-content:deploy -f th_TH```

#### Step 4: Flush cache and clean cache
Flush cache and clean cache on your Magento 2 store

```php bin/magento c:c && php bin/magento c:f```


## How to Change language

### Back-end

```
 Go to Account Settings -> Account Information -> Interface Locale -> Thai (Thailand) -> Save
```
### Front-end

```
 Go to Stores -> Settings -> Configuration -> General -> Locale Option -> Locale -> Thai (Thailand) -> Save
```

## Supported Magento versions
It supports all Magento 2 versions  

Magento v2.0.x

Magento v2.1.x

Magento v2.2.x
