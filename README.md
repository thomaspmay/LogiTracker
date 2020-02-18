MSc Computer Science
University of Bristol

```java
class Device
{
   private double maxAcceleration;
   private double minTemperature;
   private double maxTemperature;
   private double maxHumidity;
   private int    maxStationaryTime;
   
   public double  getMaxAcceleration();
   public void    setMaxAcceleration(double x);
   public double  getMinTemperature();
   public void    setMinTemperature(double x);
   public double  getMaxTemperature();
   public void    setMaxTemperature(double x);
   public double  getMaxHumidity();
   public void    setMaxHumidity(double x);
   public double  getCurrentAcceleration();
   public double  getCurrentTemperature();
   public double  getCurrentHumidity();
   public double  getCurrentLatitude();
   public double  getCurrentLongitude();
   public boolean getIncident();
   public void    setMaxStationaryTime(int x);
   private void   raiseIncident();   
}
```
