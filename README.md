import React from 'react';
import { Button, Typography, Box } from '@mui/material';

const Homepage = () => (
  <Box sx={{ padding: '2rem', textAlign: 'center' }}>
    <Typography variant="h2" gutterBottom>Snow Pro Connect</Typography>
    <Typography variant="h6" gutterBottom>
      The easiest way to connect with trusted snow removal providers near you.
    </Typography>
    <Button variant="contained" color="primary">Request Service</Button>
    <Button variant="outlined" color="secondary" sx={{ marginLeft: '1rem' }}>
      Join as Provider
    </Button>
  </Box>
);

export default Homepage;
