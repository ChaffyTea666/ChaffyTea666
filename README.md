/* Sticky header styles */
.sticky-header {
  position: fixed;
  top: -100px; /* Start the header off-screen */
  width: 100%;
  background-color: #fff;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  z-index: 1000;
  transition: top 0.3s ease; /* Smooth transition effect */
}

.sticky {
  top: 0; /* Bring the header back to the top when it becomes sticky */
}

