# SIT210-Task3.2C-ParticleIFTTT
# Note: This code is written without a light sensor using mock up values
double lightValue = 100;



void setup() {
    
    Particle.variable("sunlight", &lightValue, DOUBLE);
}

void loop() {
    
    lightValue = lightValue + 100;
    delay(1000);
}
