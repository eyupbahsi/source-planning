# ANKA Development Gantt Chart

A comprehensive project management and Gantt chart visualization tool for tracking software development projects with resource allocation, dependencies, and timeline management.

## Features

### 📊 Interactive Gantt Chart
- Visual timeline representation of development phases
- Compact date display showing only start and end dates
- Color-coded bars for different developers and project status
- Real-time updates based on service assignments
- Calendar day calculation and display

### 👥 Resource Management
- **Analysts**: Manage business analysts with start dates
- **Developers**: Assign up to 4 developers (Dev1-Dev4) with customizable names and start dates
- **Testers**: Manage QA testers with start dates
- Resource availability tracking

### 🔧 Service Management
- **Service Phases**: Organize services into multiple development phases
- **Service Categories**: Core and Product service categorization
- **Duration Management**: 
  - Development duration (business days)
  - Analysis duration
  - Testing duration
  - Buffer duration
- **Status Tracking**: Pending, In Progress, Completed statuses
- **Auto-calculation**: Automatic start and end date calculation based on dependencies and resource availability

### 🔗 Dependency Management
- Define service dependencies
- Visual dependency management through modal interface
- Automatic scheduling based on dependencies
- Circular dependency prevention

### 📈 Statistics Dashboard
- Total services count
- Completed vs in-progress services
- Total remaining work days
- Project start and end date estimates
- Resource utilization overview

### 💾 Data Management
- **Export to JSON**: Save project data in JSON format
- **Import from JSON**: Load previously saved project data
- **Export to Excel/CSV**: Export project timeline to spreadsheet format
- **Import from Excel/CSV**: Import project data from Excel files
- **Local Storage**: Automatic data persistence in browser

### 🎨 User Interface
- Clean, modern, and responsive design
- Color-coded visualization for easy status identification
- Interactive tooltips with detailed information
- Weekend highlighting in Gantt chart
- Real-time updates without page refresh

## Technology

- Pure HTML, CSS, and JavaScript (no frameworks required)
- Client-side only (no backend needed)
- LocalStorage for data persistence
- PapaParse library for CSV/Excel import/export

## Getting Started

### Local Usage

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start managing your project!

### Deployment

This is a static HTML application that can be deployed to any web hosting service.

#### GitHub Pages

1. Push this repository to GitHub
2. Go to Repository Settings > Pages
3. Select "Deploy from a branch" and choose "main" branch
4. Your site will be available at `https://username.github.io/repo-name`

#### Netlify

1. Visit [Netlify](https://www.netlify.com/) and create a free account
2. Click "Add new site" > "Deploy manually"
3. Drag and drop the `index.html` file
4. Your site is live instantly!

#### Vercel

1. Visit [Vercel](https://vercel.com/) and create a free account
2. Click "New Project"
3. Connect your GitHub repository or upload files
4. Click Deploy

## Usage

1. **Add Resources**: Configure analysts, developers, and testers with their start dates
2. **Assign Services**: Assign services to resources and set durations
3. **Set Dependencies**: Define which services depend on others
4. **View Gantt Chart**: See the visual timeline of all services
5. **Track Progress**: Update service statuses as work progresses
6. **Export Data**: Save your project data for backup or sharing

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

---

# ANKA Development Gantt Chart

Yazılım geliştirme projelerini kaynak tahsisi, bağımlılıklar ve zaman çizelgesi yönetimi ile takip etmek için kapsamlı bir proje yönetimi ve Gantt şeması görselleştirme aracı.

## Özellikler

### 📊 İnteraktif Gantt Şeması
- Geliştirme fazlarının görsel zaman çizelgesi gösterimi
- Sadece başlangıç ve bitiş tarihlerini gösteren kompakt tarih görünümü
- Farklı geliştiriciler ve proje durumları için renk kodlu çubuklar
- Servis atamalarına göre gerçek zamanlı güncellemeler
- Takvim günü hesaplama ve gösterimi

### 👥 Kaynak Yönetimi
- **Analistler**: İş analistlerini başlangıç tarihleriyle yönetme
- **Geliştiriciler**: Özelleştirilebilir isimler ve başlangıç tarihleriyle 4 geliştiriciye kadar (Dev1-Dev4) atama
- **Test Uzmanları**: Başlangıç tarihleriyle QA test uzmanlarını yönetme
- Kaynak müsaitlik takibi

### 🔧 Servis Yönetimi
- **Servis Fazları**: Servisleri birden fazla geliştirme fazına organize etme
- **Servis Kategorileri**: Core ve Product servis kategorilendirmesi
- **Süre Yönetimi**: 
  - Geliştirme süresi (iş günleri)
  - Analiz süresi
  - Test süresi
  - Tampon süresi
- **Durum Takibi**: Beklemede, Devam Ediyor, Tamamlandı durumları
- **Otomatik Hesaplama**: Bağımlılıklar ve kaynak müsaitliğine göre otomatik başlangıç ve bitiş tarihi hesaplama

### 🔗 Bağımlılık Yönetimi
- Servis bağımlılıklarını tanımlama
- Modal arayüz üzerinden görsel bağımlılık yönetimi
- Bağımlılıklara göre otomatik zamanlama
- Döngüsel bağımlılık önleme

### 📈 İstatistik Panosu
- Toplam servis sayısı
- Tamamlanan vs devam eden servisler
- Toplam kalan iş günleri
- Proje başlangıç ve bitiş tarihi tahminleri
- Kaynak kullanım özeti

### 💾 Veri Yönetimi
- **JSON'a Aktar**: Proje verilerini JSON formatında kaydetme
- **JSON'dan İçe Aktar**: Daha önce kaydedilmiş proje verilerini yükleme
- **Excel/CSV'ye Aktar**: Proje zaman çizelgesini elektronik tablo formatına aktarma
- **Excel/CSV'den İçe Aktar**: Excel dosyalarından proje verilerini içe aktarma
- **Yerel Depolama**: Tarayıcıda otomatik veri kalıcılığı

### 🎨 Kullanıcı Arayüzü
- Temiz, modern ve duyarlı tasarım
- Kolay durum tanımlaması için renk kodlu görselleştirme
- Detaylı bilgi içeren interaktif ipuçları
- Gantt şemasında hafta sonu vurgulama
- Sayfa yenilemeden gerçek zamanlı güncellemeler

## Teknoloji

- Saf HTML, CSS ve JavaScript (framework gerekmez)
- Sadece istemci tarafı (backend gerekmez)
- Veri kalıcılığı için LocalStorage
- CSV/Excel içe/dışa aktarma için PapaParse kütüphanesi

## Başlangıç

### Yerel Kullanım

1. Bu repository'yi klonlayın veya indirin
2. Herhangi bir modern web tarayıcısında `index.html` dosyasını açın
3. Projenizi yönetmeye başlayın!

### Dağıtım

Bu, herhangi bir web barındırma servisine dağıtılabilen statik bir HTML uygulamasıdır.

#### GitHub Pages

1. Bu repository'yi GitHub'a gönderin
2. Repository Ayarları > Pages bölümüne gidin
3. "Deploy from a branch" seçin ve "main" branch'ini seçin
4. Siteniz `https://kullaniciadi.github.io/repo-adi` adresinde kullanılabilir olacak

#### Netlify

1. [Netlify](https://www.netlify.com/) sitesini ziyaret edin ve ücretsiz hesap oluşturun
2. "Add new site" > "Deploy manually" seçin
3. `index.html` dosyasını sürükleyip bırakın
4. Siteniz anında yayında!

#### Vercel

1. [Vercel](https://vercel.com/) sitesini ziyaret edin ve ücretsiz hesap oluşturun
2. "New Project" butonuna tıklayın
3. GitHub repository'nizi bağlayın veya dosyaları yükleyin
4. Deploy butonuna tıklayın

## Kullanım

1. **Kaynak Ekle**: Analistler, geliştiriciler ve test uzmanlarını başlangıç tarihleriyle yapılandırın
2. **Servis Ata**: Servisleri kaynaklara atayın ve süreleri belirleyin
3. **Bağımlılıkları Ayarla**: Hangi servislerin diğerlerine bağımlı olduğunu tanımlayın
4. **Gantt Şemasını Görüntüle**: Tüm servislerin görsel zaman çizelgesini görün
5. **İlerlemeyi Takip Et**: İş ilerledikçe servis durumlarını güncelleyin
6. **Veriyi Dışa Aktar**: Yedekleme veya paylaşım için proje verilerinizi kaydedin

## Tarayıcı Desteği

Tüm modern tarayıcılarda çalışır:
- Chrome/Edge (en son sürüm)
- Firefox (en son sürüm)
- Safari (en son sürüm)
