# react-native-localstorage
Sync local storage for React-Native, Expo Compatible (Web, Android, iOS)

### Disclaimer

Original Autor yangga, It was no longer being maintained

```

https://github.com/yangga/react-native-sync-localstorage

```

## [Installation]
    npm install --save react-native-sync-localstorage

## [Usage]

### 1. Loading stored values at beginnig
    import localStorage from 'react-native-sync-localstorage'

    ...

    localStorage.getAllFromLocalStorage()
      .then(() => {
        // Do Something after loading...
      })
      .catch(err => {
        console.warn(err)
      })

### 2. Use local storage comfortable
#### 2-1. Setting
    const value = 12345
    localStorage.setItem('key', value)

#### 2-2. Getting
    localStorage.getItem('key')

#### 2-3. Deleting
    localStorage.removeItem('key')



## TODO

- [x] Make it usable again